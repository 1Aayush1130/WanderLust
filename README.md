# 🌍 Wanderlust — Travel Listing Web Application

> A full-stack travel listing platform where users can explore destinations, create listings, leave reviews, and manage their travel experiences — with authentication, CRUD operations, map integration, and a fully responsive UI.

---

## 🚀 Live Features

| Feature | Description |
|---|---|
| 🔐 User Authentication | Sign up, login, secure password hashing, session-based auth & logout |
| 🏕️ Listings Management | Add, edit, delete, and view all travel listings |
| ⭐ Reviews System | Add & delete reviews — only logged-in users can review |
| 📍 Map Integration | Interactive map showing listing location to help users visualize destinations |
| 🛡️ Authorization & Security | Only listing owners can edit/delete listings; only review authors can delete reviews |
| 🔒 Environment Variables | Sensitive config protected using `.env` |
| 📱 Responsive Design | Works seamlessly on Mobile, Tablet, Laptop & Desktop |

---

## 🛠️ Tech Stack

### Frontend
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-B4CA65?style=flat&logo=ejs&logoColor=black)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)

### Database
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-AA2929?style=flat&logoColor=white)

### Other Tools
| Tool | Purpose |
|---|---|
| Passport.js | Authentication middleware |
| Express-session | Session management |
| Cloudinary | Image upload & storage |
| Mapbox / Leaflet | Map integration |
| Flash messages | User-facing notifications |
| Method Override | REST method support (PUT/DELETE) |
| dotenv | Environment variable management |

---

## 📁 Project Structure

```
Wanderlust/
├── models/
├── routes/
├── controllers/
├── views/
├── public/
├── utils/
├── app.js
├── schema.js
└── package.json
```

---

## ⚙️ Installation Guide

### Prerequisites
- Node.js & npm installed
- MongoDB Atlas account (or local MongoDB)
- Cloudinary account (for image uploads)
- Mapbox API key

---

### Step 1 — Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/wanderlust.git
```

---

### Step 2 — Move into Project Folder

```bash
cd wanderlust
```

---

### Step 3 — Install Dependencies

```bash
npm install
```

---

### Step 4 — Set Up Environment Variables

Create a `.env` file in the root directory and add the following:

```env
ATLASDB_URL=your_mongodb_atlas_url
SECRET=your_session_secret

CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret

MAP_TOKEN=your_mapbox_token
```

---

### Step 5 — Run the Application

```bash
node app.js
```

Then open your browser and visit: **`http://localhost:8080`**

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ by <a href="https://github.com/1Aayush1130">Aayush</a></p>
