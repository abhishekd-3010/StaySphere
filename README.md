# 🏠 StaySphere

> A full-stack property rental and booking platform inspired by Airbnb.

StaySphere is a full-stack web application that allows users to discover properties, view detailed listings, manage properties, make bookings, and submit reviews.

The application follows an MVC-based architecture using **Node.js, Express.js, MongoDB, and EJS**, with **Cloudinary** for property image management and **Render** for deployment.

---

## ✨ Key Features

- 🏡 **Property Listings** – Create, view, update, and delete property listings with images, descriptions, pricing, and location details.
- 🔍 **Search & Discovery** – Browse and explore available properties.
- 🔐 **User Authentication** – Registration, login, logout, and session-based authentication.
- 🧑‍💼 **Host Management** – Manage property listings and booking information.
- 📅 **Booking System** – Manage property reservations and booking details.
- ⭐ **Reviews & Ratings** – Users can submit and manage reviews for properties.
- 📱 **Responsive UI** – Mobile-friendly interface built with EJS, HTML, CSS, JavaScript, and Bootstrap.
- ☁️ **Cloud Image Storage** – Property images managed using Cloudinary.

---

## 🛠️ Tech Stack

### 🎨 Frontend
- HTML5
- CSS3
- JavaScript
- EJS
- Bootstrap
- Font Awesome

### ⚙️ Backend
- Node.js
- Express.js

### 🗄️ Database
- MongoDB
- Mongoose

### 🔐 Authentication & Security
- Passport.js
- bcrypt
- Express Session

### ☁️ Cloud & Deployment
- Cloudinary
- Render

### 🔧 Development Tools
- Git
- GitHub
- npm

---

## 🏗️ Project Architecture

```text
                    👤 Client
                       │
                       ▼
              🎨 EJS / HTML / CSS
                       │
                       ▼
                ⚙️ Express.js
                       │
                       ▼
                  🛡️ Middleware
                       │
                       ▼
                 🎯 Controllers
                       │
                       ▼
                🗄️ Mongoose Models
                       │
                       ▼
                    MongoDB

                       │
                       ▼
                ☁️ Cloudinary
               Property Images
