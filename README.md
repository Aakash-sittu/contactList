# 📖 Simple Contact Book

A minimalistic MERN stack application where users can add and view contacts. This project is built using **Node.js (Express) for the backend** and **React (Vite) for the frontend**, with an in-memory array for storing contacts instead of a database.

---

## 🚀 Features

✅ **Add New Contacts** – Users can add contacts with Name, Email, and Phone number. ✅ **View Contacts** – Displays all added contacts. ✅ **Delete Contacts** (Bonus) – Remove a contact from the list. ✅ **Form Validation** (Bonus) – Basic validation for email format. ✅ **Minimalistic Styling** – Basic CSS for a clean UI.

---

## 🏗️ Project Structure

```
contact-book/
├── backend/
│   └── server.js          # Express server handling API requests
└── frontend/
    └── src/
        ├── App.js        # Main React component
        └── components/
            └── ContactList.js  # Component to display contacts
```

---

## ⚡ Tech Stack

### Backend (API) 🖥️

- Node.js with Express.js
- In-memory storage (No database for simplicity)

### Frontend (UI) 🎨

- React with Vite ⚡ (for fast development)
- Functional Components with Hooks
- Basic CSS for styling

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/yourusername/contact-book.git
cd contact-book
```

### 2️⃣ Backend Setup (API)

```sh
cd backend
yarn install
yarn start  # Runs the server on PORT 5000
```

### 3️⃣ Frontend Setup (React)

```sh
cd frontend
yarn install
yarn dev  # Starts the React app on localhost:5173
```

---

## 🔥 API Endpoints

| Method | Endpoint      | Description           |
| ------ | ------------- | --------------------- |
| POST   | /api/contacts | Add a new contact     |
| GET    | /api/contacts | Retrieve all contacts |

---

## 🎯 How to Use

1️⃣ Start the backend and frontend as mentioned above. 2️⃣ Open the frontend in your browser (Vite default: `http://localhost:5173`). 3️⃣ Add contacts using the form. 4️⃣ View the list of contacts. 5️⃣ (Optional) Delete contacts if the feature is implemented.




## 📜 License

This project is open-source and available under the **MIT License**.


