# 📱 Strent Frontend

## 🧾 Project Description
Strent is a secure real estate mobile web application that connects homeowners, tenants, and roommates directly — eliminating exploitative middlemen. This repository contains the frontend codebase for the Strent platform built using **React**, **Tailwind CSS**, **Vite**, and other modern web technologies. It also integrates geolocation, real-time messaging, responsive UI components, and payment systems.

---

## 📁 Project Structure
strent-frontend/
- │
- ├── public/ # Static assets
- │
- ├── src/
- │ ├── assets/ # Images and logos
- │ ├── components/ # Reusable components (Navbar, Footer, Cards, etc.)
- │ ├── pages/ # Page components (Home, Profile, Listings, etc.)
- │ ├── services/ # API calls using Axios or Fetch
- │ ├── context/ # Global state using Recoil/Context API
- │ ├── routes/ # Route management with React Router
- │ ├── utils/ # Helper functions
- │ ├── styles/ # Tailwind/CSS styles
- │ ├── App.jsx # Main App wrapper
- │ └── main.jsx # Entry point
- │
- ├── .env # Environment variables
- ├── .gitignore # Files ignored by Git
- ├── index.html # Root HTML file
- ├── package.json # Project dependencies
- └── README.md # Project info and instructions

---

## 🛠️ Tech Stack
- **React** + **Vite** (Frontend framework & bundler)
- **Tailwind CSS** (Utility-first styling)
- **Recoil / Context API** (State management)
- **Axios / Fetch API** (API integration)
- **React Router** (Routing)
- **Cloudinary / AWS S3** (Image uploads)
- **Stripe / Paystack** (Payment integration)
- **Socket.io** (Real-time messaging)
- **Formik + Yup / Alternatives** (Form validation)

---

## 🧑‍💻 Getting Started

### 📦 Prerequisites
- Node.js v16+
- npm or yarn

### ⚙️ Installation
```bash
git clone https://github.com/wendiblac/strent-frontend.git
cd strent-frontend
npm install
npm run dev
```

---

## 🚀 Deployment

We use AWS Amplify for frontend hosting.
To deploy:
- Push your code to the main or dev branch.
- Connect repo to AWS Amplify console.
- Configure build settings via amplify.yml.

## 🧭 Contribution Guidelines
🧑‍🤝‍🧑 Who Can Contribute
All team members from Frontend Development track and Cloud Engineering Track.

## 📌 Branch Naming Convention
- Feature/name = for new features
- Fix/name = for bug fixes
- Refactor/name = for code restructuring

---

## ✅ How to Contribute
- Fork the repository
- Create a new branch
- Make your changes
- Test locally
- Create a Pull Request to **dev** branch
- Tag relevant team leads for review


## 🔍 Code Style & Best Practices
- Follow Prettier rules
- Use Tailwind utility classes responsibly
- Reuse components where possible
- Keep functions pure and modular
- Use environments variables for secrets

## 🧪 Testing
- Manual component and form testing
- Add unit tests using Jest (if configured)
- Write clear commit messages.

---

## 🏗 System Architecture
graph TD
    A[User Interface - React Components] --> B[Routing - React Router]
    B --> C[State Management - Recoil/Context API]
    C --> D[API Services - Axios/Fetch]
    D --> E[Backend REST API (FastAPI)]
    E --> F[Database]
    B --> G[Real-time Updates - Socket.io]
    A --> H[Authentication - JWT/Firebase/Auth0]
    A --> I[Payments - Stripe/Paystack]


## 🧩 Future Features
- Dark/Light Mode
- Push Notifications
- In-App Chat
- Saved Listings
- Multi-Language Support

---

## 🤝 Contact
For questions, issues, or contributions, please contact the Dev Team Lead or Assistant or raise an issue in the repository, Slack Channel or Whatsapp group.


© 2025 Strent Dev Team. All rights reserved.





