![image](https://github.com/user-attachments/assets/d812f93c-5277-418c-9b28-843e16c3eca8)# 🎓 Study Notion – Full Stack EdTech Platform

**Study Notion** is a full-fledged, production-ready EdTech platform that allows instructors to create and manage courses while students can browse, purchase, and access them. Built with a modern tech stack, it simulates the real-world experience of platforms like Udemy or Coursera.

---

## 🔗 Live Demo

🚀 https://study-notion-frontend-phi-dusky.vercel.app/

---

## 📌 Key Features

### 🔐 Authentication & Authorization
- Secure **JWT-based authentication**
- **OTP verification** on signup for added security
- **Role-based access** for students and instructors

### 📚 Course Management (Instructor Panel)
- Create, edit, and categorize courses
- Upload videos, text content, and course thumbnails
- Monitor enrollments and student progress

### 👨‍🎓 Student Experience
- Browse and view available courses
- Purchase via **Razorpay** integration
- Access enrolled courses through a personalized dashboard

### 💳 Razorpay Payment Gateway
- Integrated for real-time, secure transactions
- Handles order creation and post-payment access seamlessly

### 🧩 Reusable UI Components
- 20+ **custom React components** for modularity
- Fully responsive design with **Tailwind CSS**
- Clean and intuitive interface

---

## 🧠 Tech Stack

| Layer        | Technologies                       |
|--------------|------------------------------------|
| Frontend     | React.js, Tailwind CSS             |
| Backend      | Node.js, Express.js                |
| Database     | MongoDB                            |
| Authentication | JWT, Nodemailer (OTP)           |
| Payments     | Razorpay                           |
| Deployment   | Vercel (Frontend), Render (Backend)|

---

## 🗂️ Folder Structure


---

## 📈 Functional Highlights

- 📌 JWT-secured login & signup with OTP verification
- 📌 Razorpay-based secure course purchase flow
- 📌 Protected routes based on user roles
- 📌 Dynamic dashboards for students and instructors
- 📌 Scalable architecture using modular React components and RESTful APIs

---

## 🚀 How to Run Locally

### 1. Clone the repo

```bash
git clone https://github.com/deepak00944/StudyNotion.git
cd studynotion
```
2. Setup Backend (Node.js)
```bash
cd server
npm install
# Create a `.env` file and add your MONGO_URI, JWT_SECRET, RAZORPAY_KEY, etc.
npm start

```
3. Setup Frontend (React)
```bash
cd src
npm install
npm run dev


```

4. Open in Browser
```bash
Frontend: http://localhost:5173
Backend API: http://localhost:5000
```

📷 Screenshots
![image](https://github.com/user-attachments/assets/228e29cb-7c35-47c0-bfbc-7de5b66b4b2b)
![image](https://github.com/user-attachments/assets/8778c376-4b6f-4695-b0b8-669b6af66b62)
![image](https://github.com/user-attachments/assets/5da49e19-a0de-444d-bfc7-e2213ea2584a)
![image](https://github.com/user-attachments/assets/3a69cfec-09bf-4334-9d7a-b6d81518239f)
