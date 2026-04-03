# 🏨 Hostel Management System

A modern **full-stack Hostel Management System** built to streamline hostel operations, improve communication, and enhance management efficiency. This system provides role-based access for Admins, Staff, and Students with powerful features for managing rooms, bookings, complaints, and more.

---

## 🚀 Features

* 🔐 Secure Authentication & Authorization
* 🧑‍💼 Role-Based Access (Admin / Staff / Student)
* 🛏 Room Allocation & Management
* 📋 Booking & Request Handling
* 🧾 Complaint Management System
* 📊 Dashboard with Insights
* 📧 Email Notifications Integration
* 🤖 AI Chatbot
* ☁️ Cloud Media Upload (Cloudinary)
* 🌐 Responsive UI (Mobile Friendly)

---

## 🧑‍🤝‍🧑 User Roles & Screenshots

✨ Landing Page

* ![Landing Page](src/screenshots/l1.png)
* ![Landing Page](src/screenshots/l2.png)
* ![Landing Page](src/screenshots/l3.png)
* ![Landing Page](src/screenshots/l4.png)
* ![Landing Page](src/screenshots/l5.png)
* ![Landing Page](src/screenshots/l6.png)

---

🔐 User Login

* ![Login Page](src/screenshots/login.png)

---
🔐 User Registration

* ![Register_User](src/screenshots/register.png)
* ![OTP](src/screenshots/otp.png)

### 👨‍💼 Admin Panel

> Manage users, rooms, reports, and system settings

📸 Screenshots:

* ![Admin Dashboard](src/screenshots/ad.png)
* ![Manage Users](src/screenshots/A_userManagement.png)
* ![Warden Approval](src/screenshots/A_wardenApproval.png)
* ![System Report](src/screenshots/A_systemReport.png)
* ![Announcements](src/screenshots/A_announcement.png)
* ![Admin Dashboard](src/screenshots/A_setting.png)

---

### 🧑‍🔧 Warden Panel

> Handle room allocation, complaints, and student requests

📸 Screenshots:

* ![Warden Dashboard](src/screenshots/Wd.png)
* ![Student Management](src/screenshots/W_studentManagement.png)
* ![Student Approval](src/screenshots/W_studentApproval.png)
* ![Room Management](src/screenshots/W_roomManagement.png)
* ![Complaints](src/screenshots/W_complaints.png)
* ![Inventory Management](src/screenshots/W_inventory.png)
* ![Staff Management](src/screenshots/W_staffManagement.png)
* ![Announcements](src/screenshots/W_announcement.png)

---

### 🎓 Student Panel

> Book rooms, submit complaints, and view status

📸 Screenshots:

* ![Student Dashboard](src/screenshots/Sd.png)
* ![Student Profile](src/screenshots/S_profile.png)
* ![Payments](src/screenshots/S_payment.png)
* ![Maintanance Request](src/screenshots/S_maintainance.png)
* ![Clearance](src/screenshots/S_clearance.png)
* ![AI Assistant](src/screenshots/S_AI.png)

---


## 🎥 Project Demo
Experience the HostelManagement System in action:

👉 [Watch Full Demo Video](https://drive.google.com/file/d/162HJFJlwLEbS7-1TeAsvIZJXMrF1jpSe/view?usp=sharing)

---

## 🛠️ Tech Stack

| Layer    | Technology                               |
| -------- | -----------------------------------------|
| Frontend | React.js(Vite), TypeScript, Tailwind CSS |
| Backend  | Node.js, Express.js, JavaScript          |
| Database | MongoDB                                  |

**Other Tools & Services**

* Cloudinary (Image Uploads)
* Nodemailer (Email Service)
* JWT Authentication
* AI Integration (Gemini / OpenAI)


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/hostel-management-system.git
cd hostel-management-system
```

---

### 2️⃣ Install Dependencies

```bash
npm install
cd backend
npm install
```

---

### 3️⃣ Environment Variables

Create a `.env` file inside `backend/` and add:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_KEY=your_api_key
CLOUDINARY_SECRET=your_api_secret
```

---

### 4️⃣ Run the Project

```bash
npm run dev
```

---

### 5️⃣ Open in Browser

```
http://localhost:5173
```

---

## 📁 Project Structure

```
hostel-management/
│
├── frontend/
│   ├── src/
│   └── components/
│
├── backend/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── config/
│
└── README.md
```

---

## 🔐 Security Notes

* Never expose your `.env` file publicly
* Use environment variables for sensitive data
* Regenerate API keys before deploying

---

## 🌟 Future Improvements

* 📱 Mobile App Integration
* 🔔 Real-time Notifications
* 📊 Advanced Analytics Dashboard
* 💳 Online Payment Integration


---

## 🙌 Acknowledgements

* MongoDB Atlas
* Cloudinary
* Open-source community

---

## 👨‍💻 Author

**Saubhagya**
🎓 Undergraduate IT Student
💻 Full Stack Developer

---

## 🌟 Support

If you like this project, give it a ⭐ on GitHub 🚀
