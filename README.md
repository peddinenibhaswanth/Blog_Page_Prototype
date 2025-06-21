# 📝 Blog Page Prototype (Full Stack)

This is a full-stack **Blog Page Prototype** built with **Express.js**, **Axios**, and **EJS templates**. It uses a self-contained in-memory API (`index.js`) for managing blog posts and a client-side server (`server.js`) for rendering and handling user interaction through web forms.

---

## 📁 Project Structure

```
.
├── node_modules/
├── public/
│   └── styles/
│       └── main.css
├── views/
│   ├── index.ejs
│   └── modify.ejs
├── index.js         # In-memory Blog API (acts as a mini database)
├── server.js        # Frontend-facing server (handles routes and views)
├── package.json
├── package-lock.json
└── README.md
```

---

## 🚀 How It Works

- **index.js** exposes a RESTful API to manage blog posts (`GET`, `POST`, `PATCH`, `DELETE`).
- **server.js** consumes that API using `axios` and renders UI using `EJS` templates.
- Users can:
  - View posts
  - Create a new post
  - Edit an existing post
  - Delete a post

---

## 📦 Installation

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/Blog_Page_Prototype.git
cd Blog_Page_Prototype
```

2. **Install dependencies:**
```bash
npm install
```

3. **Start both servers:**

- Start the API server (in one terminal):
```bash
node index.js
```

- Start the frontend server (in another terminal):
```bash
node server.js
```

4. **View in browser:**
Open `http://localhost:3000`

---

## 🧪 Features

- Full CRUD blog post system
- In-memory API for demonstration purposes (no database needed)
- Uses Axios to perform API calls
- Built-in templates using EJS

---

## 📌 Notes

- All data is stored in-memory. Restarting `index.js` will reset posts.
- Make sure `index.js` runs on port **4000**, and `server.js` on **3000**.
- Edit `public/styles/main.css` to customize the look.

---
