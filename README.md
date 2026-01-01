## 📝 Notes App – Frontend (React)

A modern **React-based frontend** for a full-stack Notes application, designed with **real-world UX patterns** such as optimistic UI updates, skeleton loaders, and toast feedback.

This frontend focuses on **user experience, responsiveness, and clean component architecture**.

---

## ✨ Features

* ⚡ Optimistic UI (notes appear instantly)
* 🗑️ Skeleton loader on deleting a note (per-card loading)
* 🔔 Toast notifications (Save / Update / Delete)
* 🪟 Modal-based note viewer
* ✏️ Inline edit & delete actions
* 🎯 Prevents accidental clicks with event control
* 📱 Fully responsive UI

---

## 🛠 Tech Stack

* React
* CSS Modules
* react-hot-toast
* Fetch API

---

## 📸 Screenshots

> *(Add screenshots here for maximum impact)*

* Notes grid
* Modal view
* Skeleton loader on delete
* Editor view

---

## 🧠 UX Decisions (Important)

* **Optimistic UI** improves perceived performance
* **Skeleton loaders** prevent double-click confusion during slow API calls
* **Modal reading experience** keeps navigation simple
* **Action icons** avoid accidental edits/deletes

These patterns are commonly used in production-grade applications.

---

## ⚙️ Setup & Run Locally

```bash
git clone https://github.com/your-username/notes-app-frontend.git
cd notes-app-frontend
npm install
npm run dev
```

> Make sure backend API is running and environment variables are set.

---

## 🔗 Environment Variables

Create a `.env` file:

```env
VITE_API_URL=https://your-backend-api-url
```

---

## 🔗 Live Demo

👉 **Frontend:** [https://https://notesapp-bysd.netlify.app/))

---

## 📁 Folder Structure

```
src/
 ├─ components/
    ├─ Header/
    ├─ NoteEditor/
    ├─ NoteModal/
    ├─ Sidebar/
 ├─ styles/
 ├─ App.jsx
 └─ main.jsx
```

---

## 🙋‍♂️ Author

**Saeed Ahmed**
Frontend / MERN Developer
Focused on **clean UI, UX-first design, and scalable React apps**

⭐ If you find this useful, give it a star!
