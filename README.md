# 🚀 HRXpert - Employee Management System

A full-stack Employee Management System built with:

- Frontend: React.js
- Backend: Node.js + Express.js
- Database: MongoDB
- Authentication: JWT

---

## 📥 1️⃣ Clone the Repository

```bash
git clone https://github.com/vivek-bind/HRXpert-Employee-Management-System.git
cd HRXpert-Employee-Management-System

## Install Dependencies
cd backend
npm install

cd ../frontend
npm install

## Setup Environment Variables
.env file inside the backend folder and add:
MONGO_URI=your_mongodb_connection_string
JWT_KEY=your_secret_key
PORT=3000


---------

## Seed the Database
cd backend
node seed.js

---------

## Default Accounts After Seeding

Role Email Password
Employee janesmith@example.com password12345

Account:

1 → Admin

2 → HR

3 → Employee

## Run the Application

cd backend
npm start

cd frontend
npm start

## application url

http://localhost:3000

```
