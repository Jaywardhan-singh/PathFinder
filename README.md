# Path Finder : Your Travel Companion 🌍✈️  
**AI-Powered Trip Planner built with React, Firebase, and Google APIs**

Path-Finder is a full-stack web application that helps users generate **personalized trip itineraries** using Google Places API and **Gemini AI**. It allows users to plan trips, explore destinations, and store their itineraries securely with Google authentication and Firebase.

---

## 🚀 Features

- **Landing Page & UI**
  - Modern UI built with **React + Vite**
  - Styled with **ShadCN**, Tailwind CSS, and custom components
  - Hero section and navigation for seamless flow  

- **Trip Planning**
  - Google Places Autocomplete for city selection  
  - Budget selection and trip details form  
  - AI-powered trip generation using **Gemini AI**  
  - Personalized recommendations: places to visit, best time, hotels, maps  

- **Authentication & Database**
  - Google OAuth for sign-in/sign-up  
  - Firebase for authentication, Firestore for storing user trips  
  - Token-based authentication with user profile retrieval  

- **Dynamic Routes & Data**
  - Auto-generated trip pages with unique document IDs  
  - Fetch and display user-specific trips from Firestore  
  - Responsive grid layout for daily trip plans  

- **Enhancements**
  - Skeleton loading for images and trips  
  - Smooth transitions and popovers for better UX  
  - Google Maps integration with interactive icons  

- **Deployment**
  - Deployed on **Vercel** with proper routing configuration  

---

## 🛠️ Tech Stack

- **Frontend**: React, Vite, ShadCN, Tailwind CSS  
- **Backend/Database**: Firebase Authentication, Firestore  
- **AI**: Gemini AI API (Google AI Studio)  
- **APIs**: Google Places, Google Maps  
- **Deployment**: Vercel  

---

## 📂 Project Structure
<pre>
Path-Finder/
├── src/
│ ├── components/ # UI components (Navbar, Hero, Forms, Hotels, etc.)
│ ├── pages/ # Landing, Create Trip, View Trip, Profile
│ ├── routes/ # Route configurations
│ ├── constants/ # Budget options, API config
│ ├── services/ # API calls (Google, Firebase, Gemini AI)
│ ├── utils/ # Helper functions, validation
│ ├── App.jsx # Main entry point
│ └── index.css # Global styles
├── public/ # Static assets
├── .env.local # API keys (Google, Firebase, Gemini)
├── package.json
└── README.md
</pre>

---

## ⚙️ Setup & Installation

### 1. Clone the repo
```bash
git clone https://github.com/Jaywardhan-singh/Path-Finder.git
cd Path-Finder
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configure environment variables
```bash
VITE_GOOGLE_MAPS_API_KEY=your_google_api_key
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
VITE_GEMINI_API_KEY=your_gemini_api_key
```

### 4. Run locally
```bash
npm run dev
```
---

## 🔮 Future Improvements

- Multi-user collaboration for group trips
- Offline trip saving & export as PDF
- Integration with flight & hotel booking APIs
- Advanced AI prompts for even richer recommendations
