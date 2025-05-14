# EcoCycle-food-Donation
# step  by step commands used 
  npm install 
  node server 
  npm i firebase-admin/app
  npm i firebaase-admin
  npm i password-hash
  npm i uniqid
  npm i express 
  npm i express-session 
  npm run 
  npm start 




  Here’s a professional and complete `README.md` file for your **EcoCycle – Food Waste Reduction Platform** project:

---

# 🌱 EcoCycle – Food Waste Reduction Platform

EcoCycle is a community-driven web application designed to reduce food waste by connecting individuals and organizations with surplus food to those in need. With features like real-time food listing, AI-generated descriptions, geolocation, and user ratings, EcoCycle makes food donation easy, secure, and impactful.

---

## 🚀 Key Features

* **📝 Food Donation Listings**
  Donors can list food with quantity, type, expiration date, and pickup details.

* **📍 Location-Based Search**
  Recipients can browse available food near them using integrated Google Maps.

* **🔐 Secure Authentication**
  Firebase Authentication for both donor and recipient roles.

* **🤖 AI-Powered Descriptions**
  An AI helper generates smart and appealing descriptions for food items.

* **⭐ User Ratings & Reviews**
  Build trust in the community by rating donations and experiences.

* **📬 Messaging System**
  Enables real-time communication between donors and recipients.

---

## 🛠️ Tech Stack

### 🖥️ Frontend:

* EJS (Embedded JavaScript)
* HTML/CSS
* JavaScript

### 🌐 Backend:

* Node.js
* Express.js

### ☁️ Database & Authentication:

* Firebase (Cloud Firestore)
* Firebase Authentication

### 📦 Other Libraries:

* `firebase-admin` – Admin access to Firebase
* `body-parser` – Middleware for parsing incoming requests
* `express-session` – User session management
* `password-hash` – Secure password handling
* `uniqid` – Unique ID generation

---

## 🏗️ Folder Structure

```
/ecocycle
├── views/                   # EJS templates
│   ├── org_register.ejs
│   ├── don_register.ejs
│   └── org_home.ejs
├── public/                  # Static assets (CSS, images)
├── routes/                  # Route handlers
├── app.js                   # Main server file
├── firebase/
│   └── key.json             # Firebase credentials
└── README.md
```

---

## 📸 Screenshots

![Homepage](https://your-image-link.com)

> *Homepage connecting donors and recipients*

---

## 🔐 How to Run Locally

1. Clone the repo

   ```bash
   git clone https://github.com/yourusername/ecocycle.git
   cd ecocycle
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Add Firebase credentials to `firebase/key.json`.

4. Start the server

   ```bash
   node app.js
   ```

5. Visit `http://localhost:3000` in your browser.

---

## 🤝 Contribution

Pull requests are welcome! If you have ideas to improve features or UI, feel free to open an issue.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Developed By

**G. Laxmi Narsimha Swamy**
*Frontend Developer | Backend Enthusiast | Social Impact Builder*

---

Would you like a PDF version of this README or help hosting this on GitHub or Vercel?
