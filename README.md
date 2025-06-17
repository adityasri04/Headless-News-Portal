
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

```
Headless-News-Portal/
├── public/
├── src/
│   ├── components/       # PostCard, Header, Footer
│   ├── pages/            # Home, PostDetail, CategoryPage
│   ├── services/         # API wrappers
│   ├── hooks/            # Custom hooks for data fetching
│   ├── App.js
│   └── index.js
├── .env.local            # API base URL config
└── README.md
```

---

## ⚙️ Setup Instructions

### Backend (WordPress)

1. Install WordPress locally or on a server.
2. Ensure permalinks are enabled.
3. (Optional) Install **JWT Authentication** or **CORS Enabler** plugins.
4. REST endpoints (test in browser):
   - `https://yourdomain.com/wp-json/wp/v2/posts`
   - `https://yourdomain.com/wp-json/wp/v2/categories`

### Frontend (React)

1. Clone this repository:

```bash
git clone https://github.com/adityasri04/Headless-News-Portal.git
cd Headless-News-Portal
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Create a `.env.local` file in the root:

```env
REACT_APP_API_URL=https://yourwordpressdomain.com/wp-json/wp/v2
```

4. Start the dev server:

```bash
npm start
# or
yarn start
```

---

## 🧩 Core Components

### ✅ `PostCard.js`

Displays a blog summary card with title, excerpt, and featured image.

### ✅ `PostDetail.js`

Dynamic route page to fetch and display a full blog post via REST API.

### ✅ `CategoryPage.js`

Renders posts filtered by category using the `/posts?categories=<id>` endpoint.

---

## 📈 Possible Enhancements

- 🔍 Search functionality using `/posts?search=`
- 🛂 JWT authentication with login/logout
- 💬 WordPress comment integration
- 🌐 Infinite scroll or pagination
- 📱 Offline support / PWA capabilities
- 🧪 Unit tests with Jest

---

## 🧾 Resume Summary (Optional)

> **Headless News Portal** – React Frontend with WordPress CMS (REST API)  
> • Built a decoupled blog system using WordPress as backend and React as frontend.  
> • Integrated dynamic routing, RESTful API calls, and real-time data fetching with Axios.  
> • Designed a responsive, SEO-optimized UI with category filtering and post detail routing.

---

## 📦 Deployment

- Host React app on **Vercel**, **Netlify**, or similar.
- Ensure WordPress is publicly accessible and REST API CORS is enabled.
- Configure `.env.local` with your live API URL.

---

## 🧠 Contributing

Pull requests are welcome!

```bash
git checkout -b feature/myFeature
git commit -m "Added myFeature"
git push origin feature/myFeature
```
---

## 📬 Contact

Made with ❤️ by [Aditya Srivastava](https://github.com/adityasri04)
