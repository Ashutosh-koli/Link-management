# 🔗 MERN URL Shortener

A simple and efficient URL Shortener application built using the MERN stack (MongoDB, Express.js, React, Node.js).

## 🚀 Features

- Shorten long URLs into concise, shareable links
- Redirect to original URL using the short code
- Track total clicks (optional)
- Clean, responsive frontend
- RESTful API integration
- MongoDB for persistent storage

## 🛠️ Tech Stack

**Frontend:**
- React (with Vite)
- Axios for API requests
- CSS (fully responsive)

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- ShortID or NanoID for generating unique short links

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/Ashutosh-koli/Link-management.git
cd mern-url-shortener
```

### 2. Set up the backend
```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` directory:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
BASE_URL=http://localhost:5000
```

Start the backend:
```bash
npm start
```

### 3. Set up the frontend
```bash
cd ../frontend
npm install
npm run dev
```

> The frontend will run on `http://localhost:5173` and the backend on `http://localhost:5000`.

## 📂 Project Structure

```
mern-url-shortener/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── .env
│   └── server.js
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   └── App.jsx
│   └── vite.config.js
│
└── README.md
```

## 🧪 Example API Routes

- `POST /api/shorten` - Submit a long URL and receive a short URL
- `GET /:shortCode` - Redirect to the original long URL

## 📸 Screenshots

![Sign-up](https://github.com/user-attachments/assets/f4204185-4a11-4519-9f64-eeb19a291aef)
![Login](https://github.com/user-attachments/assets/b6d98ded-6a51-4bf9-86b1-010167835667)
![Dashboard](https://github.com/user-attachments/assets/b8d14ceb-8bc8-4fcd-b8ff-b9540b6dfad5)
![Links](https://github.com/user-attachments/assets/f269b7a4-58c0-4f78-970d-81628c04bd3a)
![New link](https://github.com/user-attachments/assets/5e98de4a-63bb-4c4a-8036-86d0362cfaaf)
![Edit link](https://github.com/user-attachments/assets/04cd3b30-fdeb-4c0b-9855-b2ae8f21d429)
![analytics](https://github.com/user-attachments/assets/5c50eb00-3733-4141-bbf1-0ad1629f4ffa)
![settings](https://github.com/user-attachments/assets/23e035ca-fcaf-4593-bfd3-0294381d8df0)


## 📃 License

This project is licensed under the MIT License.

---

Feel free to fork and contribute to this project!
