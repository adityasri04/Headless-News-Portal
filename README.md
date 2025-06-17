# 📰 Headless News Portal

A modern decoupled news/blog platform where **WordPress** acts as the backend CMS and **React.js** serves as the frontend using the WordPress REST API.

Built to demonstrate scalable, responsive, and SEO-friendly blog architecture using clean code practices and RESTful integrations.

---

## 🚀 Features

- 📄 Dynamic post listing and detailed views
- 🧭 Routing for individual posts, categories
- 🔎 Category-based filtering
- ⚡ Fast, responsive, mobile-first design
- 🧠 State management using Context/Redux
- 🔌 Fetching posts from WordPress REST API

---

## 🛠 Tech Stack

- **Frontend**: React.js, React Router, Axios
- **Backend**: WordPress (as Headless CMS)
- **API**: WordPress REST API (`/wp-json/wp/v2`)
- **Styling**: CSS Modules / Tailwind / Styled Components (based on your setup)

---

## 📁 Folder Structure

Headless-News-Portal/
├── public/
├── src/
│ ├── components/ # PostCard, Header, Footer
│ ├── pages/ # Home, PostDetail, CategoryPage
│ ├── services/ # API wrappers
│ ├── hooks/ # Custom hooks for data fetching
│ ├── App.js
│ └── index.js
├── .env.local # API base URL config
└── README.md
