# 🍔 Food Delivery Web Application

A **Full Stack Food Delivery Web Application** built with **Spring Boot (Backend)** and **React.js (Frontend)**.  
It allows users to browse food items, place orders, and manage them with a simple and user-friendly interface.  
The project also includes an **Admin Panel** to manage restaurants and menu items.

---

## 🚀 Features
- User Registration & Login (Authentication)  
- Browse restaurants and food items  
- Add to Cart & Place Orders  
- Admin panel to manage restaurants and menu items  
- MongoDB for database storage  
- Responsive and user-friendly UI  

---

## 🛠️ Tech Stack
- **Backend:** Spring Boot, Java, MongoDB  
- **Frontend:** React.js, Vite, Tailwind CSS  
- **Database:** MongoDB  

---

## ⚙️ Steps to Run the Project

### 1. Download & Extract
- Download the project ZIP and extract it.  

### 2. Setup MongoDB
- Create a database (example: `food_delivery_db`).  
- Update the database name in your `application.properties` if required:
  ```properties
  spring.data.mongodb.uri = mongodb://localhost:27017/food_delivery_db
3. Start Backend (Spring Boot)

Open the backend folder in an IDE (IntelliJ / Eclipse / VS Code).

Run the Spring Boot application.

The backend will start on port 8080.

4. Start Admin Panel (Frontend - React)
cd adminpanel
npm install
npm run dev


Open browser and navigate to 👉 http://localhost:5173

5. Start User Application (Frontend - React)
cd foodies
npm install
npm run dev


Open browser and navigate to 👉 http://localhost:5174 
