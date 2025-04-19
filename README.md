# 🏠 Roommate Finder Web App

A fullstack roommate and room-searching web app built with **Nuxt 3**, **Firebase**, **Node.js**, and **Google APIs** (Maps, Places, Routes). The app features intelligent matching for roommates and rooms, real-time chat functionality, and advanced distance and travel duration calculations.

---

## 🚀 Key Features

- **🔐 Authentication:**

  - Secure login with Firebase Authentication (email/password, Google Sign-In).

- **🤝 Matching System:**

  - Matches **roommates to roommates** and **roommates to rooms** based on user preferences.
  - Advanced scoring system ensuring relevant and accurate matches.

- **💬 Real-Time Chat:**

  - Instant messaging using Firebase real-time database.
  - Real-time notifications and live chat updates.

- **🗺️ Distance & Travel Duration:**

  - Calculates precise distances and durations (car, public transit, walking) using Google Routes API.
  - Interactive maps for room location visualization powered by Google Maps & Places API.

---

## 🌐 Tech Stack

- **Frontend:** Nuxt 3 (Vue.js Composition API)
- **Backend:** Node.js & Firebase Cloud Functions
- **Database:** Firestore
- **Authentication:** Firebase Auth
- **APIs:** Google Maps, Google Places, Google Routes

---

## 📂 Project Structure

```
roommate-finder/
├── components/         # Vue components
├── pages/              # Nuxt pages and routing
├── composables/        # Reusable logic
├── utils/              # Helper functions
├── firebase/           # Firebase config
├── functions/          # Firebase Cloud Functions
└── assets/             # Images and icons
```

---

## ⚙️ Setup & Installation

### Prerequisites

- Node.js (v18 or higher recommended)
- Firebase CLI
- Google API credentials

### Installation Steps

Clone this repository:

```bash
git clone https://github.com/your-username/roommate-finder.git
cd roommate-finder
npm install
```

Set up your `.env` file with your credentials:

```env
NUXT_FIREBASE_API_KEY=your_firebase_api_key
NUXT_FIREBASE_PROJECT_ID=your_project_id
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

Run the development server:

```bash
npm run dev
```

Deploy Firebase Functions:

```bash
cd functions
npm install
firebase deploy --only functions
```

---

## 📸 Screenshots

<img width="1268" alt="1" src="https://github.com/user-attachments/assets/4d420d79-b2f8-47ca-bbed-ff4bda338d2f" />
<img width="659" alt="2" src="https://github.com/user-attachments/assets/6956ae72-cfad-4365-9c4b-419d033de16c" />
<img width="638" alt="3" src="https://github.com/user-attachments/assets/454030c6-9072-491d-b61e-ef6c467cc9fb" />
<img width="643" alt="4" src="https://github.com/user-attachments/assets/5bcecb0b-4450-4c34-a499-381b666b8a46" />
<img width="1034" alt="5" src="https://github.com/user-attachments/assets/17718b84-ba71-4626-941d-a656fc89bf28" />
<img width="1280" alt="6" src="https://github.com/user-attachments/assets/e58335ad-654a-442c-b455-37df042aa67e" />


---

## 📅 Future Improvements

- Use AI for matching
- Update filters
