# 🌍 WanderLust — Full-Stack Travel Listing Web Application

WanderLust is a full-stack **travel and accommodation listing platform** inspired by modern rental and travel websites. The application allows users to **explore destinations, create listings, write reviews, and manage content securely**. It is built using **Node.js, Express, MongoDB**, and **EJS**, following the MVC architecture.

This project demonstrates strong backend fundamentals, authentication, authorization, and CRUD operations, making it ideal for **internship applications and academic projects**.

---

## 🚀 Live Demo

* **Deployed Application:** [https://wanderlust-xz5o.onrender.com](https://wanderlust-xz5o.onrender.com)

---

## ✨ Features

* 🔐 User authentication & authorization (Login / Signup)
* 🏠 Create, edit, and delete travel listings
* 📝 Add and manage reviews for listings
* 👤 User-specific content control (only owners can edit/delete)
* 📸 Image upload support with cloud configuration
* 🛡️ Secure routes using middleware
* 📦 MVC architecture for clean code structure
* 🌐 Server-side rendered views using EJS

---

## 🛠️ Tech Stack

### Frontend (Server-Side Rendering)

* EJS (Embedded JavaScript Templates)
* HTML5
* CSS3
* Bootstrap

### Backend

* Node.js
* Express.js
* MongoDB & Mongoose
* Passport.js (Authentication)
* Express-Session
* Method-Override

### Database

* MongoDB Atlas (Cloud Database)

### Deployment

* Render

---

## 📸 Screenshots

> Add screenshots of your project UI below (home page, listing page, review section, login/signup, etc.)

```
/screenshots
 ├── home.png
 ├── listing.png
 ├── add-listing.png
 ├── reviews.png
 └── login.png
```

---

## 📁 Project Structure

```
wanderlust/
│
├── controllers/
├── init/
├── models/
├── public/
├── routes/
├── utils/
├── views/
│
├── app.js
├── cloudConfig.js
├── middleware.js
├── schema.js
├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ How to Run Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/wanderlust.git
cd wanderlust
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Environment Variables

Create a `.env` file in the root directory:

```env
CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
SESSION_SECRET=your_session_secret
MONGO_URI=your_mongodb_atlas_uri
```

---

### 4️⃣ Run the Application

```bash
npm start
```

Server will run at:

```
http://localhost:3000
```

---

## 🔐 Security Highlights

* Authentication using Passport.js
* Authorization checks for protected actions
* Secure session management
* Data validation using schemas
* Middleware-protected routes

---

## 🎯 Use Cases

* Travel & accommodation listing platform
* CRUD-based full-stack project demo
* Backend-focused internship project
* Academic / college submission

---

## 📞 Contact

**Developer:** MD SARFARAZ ALAM
**Email:** [mdsarfarazalam669@gmail.com](mailto:mdsarfarazalam669@gmail.com)
**GitHub:** [https://github.com/Sarfarazsfz](https://github.com/Sarfarazsfz)

---

## ❤️ Acknowledgements

Inspired by modern travel platforms and built to strengthen **full-stack web development fundamentals**.

> *WanderLust — Explore destinations, share experiences, and travel smarter.* 🌍
