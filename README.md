Odoo_Hackathon_AHVG

# ♻️ ReWear – Sustainable Fashion Exchange Platform

**ReWear** is a web-based platform that promotes eco-friendly clothing exchange through a point-based system. It enables users to list pre-loved clothes, earn points, and redeem unique fashion items—all while contributing to reducing textile waste.

---

## 🏆 Built for OODO Hackathon – 12th July 2025

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
├── App.jsx                  # Main component with route definitions
├── main.jsx                 # Entry point of the React app
│
├── contexts/
│   └── AuthContext.jsx      # Manages user authentication state
│
├── components/
│   ├── Layout/
│   │   ├── Header.jsx       # Navigation bar shown on all pages
│   │   └── Footer.jsx       # Footer at the bottom of every page
│   ├── ProtectedRoute.jsx   # Restricts access to logged-in users
│   └── AdminRoute.jsx       # Restricts access to admin-only routes
│
├── pages/
│   ├── Landing.jsx          # Home page with intro, featured items, testimonials
│   ├── Browse.jsx           # Lists all available clothing items
│   ├── ItemDetail.jsx       # Detailed view of a single item
│   ├── Dashboard.jsx        # User dashboard with personal activity
│   ├── AddItem.jsx          # Form to upload clothing items
│
│   ├── Auth/
│   │   ├── Login.jsx        # User login form
│   │   └── Signup.jsx       # User signup form
│
│   └── Admin/
│       ├── AdminLogin.jsx   # Admin login screen
│       └── AdminDashboard.jsx # Dashboard for admin controls


---

## 🧪 How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/rewear.git
   cd rewear

2. **Install Dependencies*
   npm install

3. **Start Development Server**
   npm run dev
   
