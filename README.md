# Job Tracker Application

A modern, feature-rich job application tracker to simplify your job search process. With a sleek dark theme and intuitive Kanban board, this app helps you manage and track your job applications efficiently.

---

## 🌟 Features
- **Kanban Board:** Visualize your job application pipeline with columns for each status (Wishlist, Applied, Interviewing, Accepted, Rejected).
- **Full Application Management:** Add, edit, and track job applications with details like company, position, status, location, salary (€), deadlines, interview dates, notes, and job URLs.
- **Smart Filtering & Search:** Quickly find applications by company, position, or location.
- **Responsive Design:** Optimized for desktop, tablet, and mobile.
- **Persistent Storage:** Data saved securely to your account (via Firebase) and local storage.
- **Email Notifications:** Get automatic reminders before interviews.
- **User Authentication:** Secure signup/login with email and password.

---

## 🚀 Live Demo
> _Deploy your app and add the link below!_

[Live Demo](https://your-live-demo-link.com)

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- npm (comes with Node.js)

### 1. Clone the Repository
```bash
git clone https://github.com/sayf20/job-tracker-application.git
cd job-tracker-application
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Set Up Firebase
- Create a free [Firebase](https://firebase.google.com/) project.
- Register a web app and enable **Authentication (Email/Password)** and **Firestore Database**.
- Copy your Firebase config and create a `.env` file in the project root:
  ```env
  VITE_FIREBASE_API_KEY=your_api_key
  VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
  VITE_FIREBASE_PROJECT_ID=your_project_id
  VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
  VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
  VITE_FIREBASE_APP_ID=your_app_id
  ```
- **Do not share or commit your `.env` file!**

### 4. Start the App
```bash
npm run dev
```
- Open [http://localhost:5173/](http://localhost:5173/) in your browser.

---

## 🛠️ Tech Stack
- **Frontend:** React, TypeScript, Vite
- **Styling:** Tailwind CSS, dark theme
- **Icons:** Lucide React
- **State Management:** LocalStorage, Firebase
- **Notifications:** Email.js

---

## 🤝 Contributing
Contributions are welcome! Please fork the repo and submit a pull request.

---

## 📧 Support
For issues or suggestions, open an issue or contact [mosratisayf20@gmail.com](mailto:mosratisayf20@gmail.com).

---

**Built with ❤️ by Saifeddine Mosrati**

---

## ⚠️ Environment Variables
- **Never commit your `.env` file!**
- Add `.env` to your `.gitignore` to keep your credentials safe.
