Odoo_Hackathon_AHVG

# ♻️ ReWear – Sustainable Fashion Exchange Platform

**ReWear** is a web-based platform that promotes eco-friendly clothing exchange through a point-based system. It enables users to list pre-loved clothes, earn points, and redeem unique fashion items—all while contributing to reducing textile waste.

---

## 🏆 Built for OODO Hackathon – 9th July 2025

This project was developed within **a limited time (9 AM – 5 PM)** during the **OODO Hackathon 2025**.  
It was a result of excellent **team collaboration**, brainstorming, and problem-solving in a real-world simulation environment.

---

## 🚀 Features

- 🧥 **List Your Items:** Upload and describe items to exchange.
- 🔄 **Earn & Spend Points:** Use points earned by listing items to claim new ones.
- 🔒 **Authentication:** Login, Signup, and Protected Dashboard.
- 📦 **Browse Collection:** View listed items by others.
- 👑 **Admin Panel:** Admin-only login and control panel.
- 📊 **Impact Stats:** Track user contributions and platform growth.
- 🧑‍💻 **Responsive Design:** Built with TailwindCSS and animations via Framer Motion.

---

## 🧑‍💻 Tech Stack

| Technology       | Usage                            |
|------------------|----------------------------------|
| React.js         | Frontend Framework               |
| React Router     | Routing between pages            |
| Tailwind CSS     | Styling and responsive UI        |
| Framer Motion    | Animations and transitions       |
| Lucide Icons     | Icon set                         |
| Firebase (Optional) | For Authentication and Storage |

---

## 📁 Folder Structure & Component Breakdown

src/
├── App.jsx # Main App with routes
├── main.jsx # React app entry point
├── contexts/
│ └── AuthContext.jsx # Authentication logic
├── components/
│ ├── Layout/
│ │ ├── Header.jsx # Navigation bar at top
│ │ └── Footer.jsx # Footer section
│ ├── ProtectedRoute.jsx # Route guard for user dashboard
│ └── AdminRoute.jsx # Route guard for admin dashboard
├── pages/
│ ├── Landing.jsx # Home page with hero, stats, featured items
│ ├── Browse.jsx # Shows all listed items
│ ├── Dashboard.jsx # User-specific dashboard
│ ├── AddItem.jsx # Form to upload clothing items
│ ├── ItemDetail.jsx # Detailed view of a single item
│ └── Auth/
│ ├── Login.jsx # User login form
│ └── Signup.jsx # User signup form
│ └── Admin/
│ ├── AdminLogin.jsx # Admin login interface
│ └── AdminDashboard.jsx# Admin control panel


---

## 🧪 How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/rewear.git
   cd rewear
