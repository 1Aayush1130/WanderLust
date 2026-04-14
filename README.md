🌍 Wanderlust – Travel Listing Web Application

Wanderlust is a full-stack travel listing web application where users can explore destinations, create listings, leave reviews, and manage their travel experiences. It provides authentication, CRUD functionality, map integration, and a responsive UI for both mobile and desktop users.

This project demonstrates strong skills in Node.js, Express.js, MongoDB, EJS, authentication, REST APIs, and responsive UI design.

🚀 Live Features
👤 User Authentication
Sign up and login system
Secure password hashing
Session-based authentication
Logout functionality
🏡 Listings Management
Add new travel listings
Edit existing listings
Delete listings
View all listings
View individual listing details
⭐ Reviews System
Add reviews to listings
Delete reviews
Only logged-in users can review
📍 Map Integration
Interactive map showing listing location
Helps users visualize destinations easily
🛡 Authorization & Security
Only listing owners can edit/delete listings
Only review authors can delete reviews
Environment variables protected using .env
📱 Responsive Design
Works smoothly on:
Mobile
Tablet
Laptop
Desktop
🛠 Tech Stack
Frontend
HTML
CSS
Bootstrap
EJS
Backend
Node.js
Express.js
Database
MongoDB Atlas
Mongoose
Authentication
Passport.js
Express-session
Other Tools
Cloudinary (image upload)
Map integration (Mapbox / Leaflet)
Flash messages
Method override
dotenv
📂 Project Structure
Wanderlust
│
├── models/
├── routes/
├── controllers/
├── views/
├── public/
├── utils/
├── app.js
├── schema.js
└── package.json
⚙️ Installation Guide

Follow these steps to run locally:

Step 1

Clone repository

git clone https://github.com/YOUR_USERNAME/wanderlust.git
Step 2

Move into project folder

cd wanderlust
Step 3

Install dependencies

npm install
Step 4

Create .env file

ATLASDB_URL=your_mongodb_connection_string
SECRET=session_secret_key
CLOUDINARY_CLOUD_NAME=xxxx
CLOUDINARY_KEY=xxxx
CLOUDINARY_SECRET=xxxx
MAP_TOKEN=xxxx
Step 5

Run project

nodemon app.js

Visit:

http://localhost:3000
📸 Key Functional Modules
Authentication Module

Handles login/signup/logout securely using Passport.js

Listings Module

Allows users to create and manage travel destinations

Reviews Module

Users can share experiences and feedback

Map Module

Displays listing location interactively

🔐 Environment Variables Used
ATLASDB_URL
SECRET
CLOUDINARY_CLOUD_NAME
CLOUDINARY_KEY
CLOUDINARY_SECRET
MAP_TOKEN
🎯 Learning Outcomes From This Project

Through this project, I learned:

Full-stack application architecture
RESTful routing
Authentication & authorization
MongoDB schema design
MVC project structure
Flash messaging system
Image upload handling
Map API integration
Responsive UI development
📌 Future Improvements

Planned upgrades:

Wishlist / Favorites feature
Search & filter system
Booking functionality
Payment integration
Admin dashboard
👨‍💻 Author

Aayush Rathore

GitHub:

https://github.com/YOUR_USERNAME
⭐ Support

If you like this project, consider giving it a star on GitHub!
