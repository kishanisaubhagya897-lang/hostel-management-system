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

## 🛠 Tech Stack

**Frontend**

* React.js (Vite)
* Tailwind CSS / CSS

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB Atlas

**Other Tools**

* Cloudinary (Image Uploads)
* Nodemailer (Email Service)
* JWT Authentication

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

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

* MongoDB Atlas
* Cloudinary
* Open-source community

---

## 💡 Author

**Mohamed Sasan**
🎓 IT Undergraduate | 💻 Full-Stack Developer

---

⭐ If you like this project, don't forget to **star the repository!**
