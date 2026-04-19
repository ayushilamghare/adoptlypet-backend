# 🐾 Adoptly — Backend

Backend API for a pet adoption platform connecting adopters, shelters, and foster parents.

Built with Node.js, Express, MongoDB, JWT, and Nodemailer.

🚀 Features
Pet Listings: Add/manage pets with details (breed, age, medical info, images)
Adoption Applications: Apply, track status, and manage approvals
Search & Filters: Find pets by breed, age, size, location
User System: Auth, profiles, saved pets, application tracking
Foster System: Users can foster and manage pets
Reviews & Ratings: Feedback for shelters and pets
Messaging & Scheduling: Connect adopters with shelters
Email Notifications: Updates on applications & new listings
🛠 Tech Stack

## 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB Atlas + Mongoose
- JWT (Bearer tokens)
- Nodemailer

## 🚀 Local Setup

### Prerequisites
- Node.js ≥ 18
- A MongoDB Atlas cluster (or local MongoDB)
- An SMTP email account (e.g. Gmail App Password)

### 1. Install dependencies

```bash
npm install
```

### 2. Run the app

```bash
npm run dev
```

The API will run at **http://localhost:5001**.

## 🌍 Deployment

### Render

1. Push your `backend/` folder to a GitHub repository.
2. Create a new **Web Service** on [Render](https://render.com).
3. Set **Build Command**: `npm install`
4. Set **Start Command**: `node server.js`
5. Add all variables from `backend/.env` under **Environment → Environment Variables**.
