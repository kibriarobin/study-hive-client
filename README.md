# 📚 Study Hive

An educational platform designed to streamline learning management with a focus on user experience and administrative efficiency — built with the MERN stack.

**🔗 Live Link:** [study-hive-388ef.web.app](https://study-hive-388ef.web.app)

**📂 Category:** Educational Platform

<img width="1349" height="500" alt="image" src="https://github.com/user-attachments/assets/56518665-15ad-49a4-80e6-719c53bf4cd7" />


## 📖 Project Overview

Study Hive is an educational platform designed to streamline learning management with a focus on user experience and administrative efficiency. Implemented using the MERN stack, it offers a responsive and secure environment for students, teachers, and administrators alike. Key features include dynamic class management, interactive dashboards, secure authentication, and seamless payment integration.

## ✨ Features

- MERN stack implementation
- Responsive design
- Secure and persistent user sessions
- User-friendly interface
- Dynamic homepage
- Class management
- Interactive student dashboard
- Admin dashboard for efficient management
- Teacher application and management
- Feedback and evaluation system
- Secure authentication
- Payment method integration (Stripe)

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Firebase Authentication
- **Payment:** Stripe
- **Deployment:** Firebase Hosting

## 📦 Dependencies

- @stripe/react-stripe-js
- @stripe/stripe-js
- axios
- firebase
- react-router-dom
- recharts (for admin dashboard charts)

## 🚀 Getting Started (Run Locally)

**1. Clone the repository**
```bash
git clone https://github.com/kibriarobin/study-hive-client.git
cd study-hive-client
```

**2. Install dependencies**
```bash
npm install
```

**3. Set up environment variables**
Create a `.env` file in the root directory with your Firebase config, Stripe key, and backend API URL:
```
VITE_apiKey=your_firebase_api_key
VITE_authDomain=your_firebase_auth_domain
VITE_projectId=your_firebase_project_id
VITE_storageBucket=your_firebase_storage_bucket
VITE_messagingSenderId=your_firebase_messaging_sender_id
VITE_appId=your_firebase_app_id
VITE_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
VITE_API_URL=your_backend_api_url
```

**4. Run the development server**
```bash
npm run dev
```

The app will be running at `http://localhost:5173`

## 🔗 Links

- **Live Site:** [study-hive-388ef.web.app](https://study-hive-388ef.web.app)
- **Client Repo:** [github.com/kibriarobin/study-hive-client](https://github.com/kibriarobin/study-hive-client)
- **Server Repo:** [github.com/kibriarobin/study-hive-server](https://github.com/kibriarobin/study-hive-server)
