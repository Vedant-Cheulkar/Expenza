# 📱 Expenza

![Expenza Banner](/Frontend//assets/images/banner.png)

[![React Native](https://img.shields.io/badge/React%20Native-0.74-blue?style=for-the-badge&logo=react)](https://reactnative.dev/)  
[![Expo](https://img.shields.io/badge/Expo-51.0-black?style=for-the-badge&logo=expo)](https://expo.dev/)  
[![Node.js](https://img.shields.io/badge/Node.js-Express-green?style=for-the-badge&logo=node.js)](https://expressjs.com/)  
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-336791?style=for-the-badge&logo=postgresql)](https://neon.tech/)  
[![Clerk](https://img.shields.io/badge/Auth-Clerk-purple?style=for-the-badge&logo=clerk)](https://clerk.com/)  
[![Redis](https://img.shields.io/badge/Rate%20Limiting-Redis-red?style=for-the-badge&logo=redis)](https://redis.io/)  

**Expenza** is a simple and intuitive expense manager app where users can add incomes and expenses, track transactions in real time, and manage their financial entries with ease.  

---

## ✨ Features

- 🔐 **Authentication** with email verification using Clerk  
- 📝 **Signup & Login** flows with 6-digit email code  
- 🏠 **Home Screen** displaying current balance & past transactions  
- ➕ **Add Transactions** (Income or Expense)  
- 🔄 **Pull-to-refresh** functionality built from scratch  
- 🗑️ **Delete Transactions** to update balance instantly  
- 🚪 **Logout** to navigate back to the login screen  

---

## 🛠️ Tech Stack

- **Frontend:** React Native & Expo  
- **Backend:** Express API with PostgreSQL (Neon)  
- **Authentication:** Clerk (email verification)  
- **Navigation:** React Navigation  
- **Database:** PostgreSQL  
- **Rate Limiting:** Redis  

---

## ⚡ Installation Instructions

### 1️⃣ Backend Setup
```bash
cd backend
npm install
npm run dev
```
### 2️⃣ Frontend Setup
```bash
cd Frontend
npm install
npx expo start

---
```
## 🔑 Environment Variables
```bash
PORT=5001
NODE_ENV=development

CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
CLERK_SECRET_KEY=<your_clerk_secret_key>

DATABASE_URL=<your_neon_postgres_connection_url>

REDIS_URL=<your_redis_connection_url>
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_key>
