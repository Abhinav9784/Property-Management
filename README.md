# Estate Craft - Real Estate Management Platform

Estate Craft is a real estate management platform using the MERN stack. It supports admins, employees, sellers, and buyers. The platform is secure, responsive, and easy to use.

---

## Features

- Multi-User Roles: Buyer, Seller, Employee, Admin
- Authentication & Authorization (JWT & Redux)
- Secure Platform
- User Confidentiality
- Feedback System
- Advertisement Page for Sellers
- Property Details & Images
- Dashboards (Seller, Employee, Admin)
- Admin Analytics
- Payment Integration (Stripe)
- Save Favourites
- Buy Properties (Land, House, Villa, Apartment)
- Responsive Design
- User-Friendly Interface

---

## Technology Stack

### FRONTEND (`/frontend`)
- React.js
- Redux
- HTML, CSS, JavaScript
- Axios
- React Router
- Styled Components
- Toast Notifications

### BACKEND (`/backend`)
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT (Authentication)
- Multer (File Uploads)
- Stripe (Payments)
- Redis (Caching)
- Swagger (API Docs)
- dotenv (Environment Variables)
- bcrypt (Password Hashing)
- CORS

### DEVOPS & DEPLOYMENT
- Docker
- Docker Compose

---

## Project Structure

```
/backend         # Node.js/Express backend
/frontend        # React frontend
/docker-compose.yml
/README.md
```

---

## Installation

1. Download or clone the project.
2. Make sure you have **Node.js**, **npm**, and **Docker** installed.

---

## Running Locally (Without Docker)

Open two terminals.

### 1. Backend

```bash
cd backend
npm install
npm run dev
```

### 2. Frontend

```bash
cd frontend
npm install
npm start
```

---

## Running with Docker

Make sure Docker is running.

```bash
docker-compose up --build
```

- Frontend: [http://localhost:3000](http://localhost:3000)
- Backend API: [http://localhost:5000](http://localhost:5000)

To stop:

```bash
docker-compose down
```

