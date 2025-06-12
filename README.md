# 🧾 Result Management System

A web-based Result Management System that allows administrators and educational institutions to efficiently manage student results, grades, and performance records. The project simplifies the process of recording, updating, and viewing academic results.

---

## 📌 Key Features

### 👨‍🎓 Students:
- View individual subject marks and overall grades
- Download mark sheets (optional PDF feature)
- User-friendly interface for quick access

### 🧑‍🏫 Admin/Staff:
- Add and manage student data
- Enter and update subject-wise marks
- Generate consolidated results
- Secure login system for admin access

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript, EJS (Embedded JavaScript Templates)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (or JSON files for simpler version)
- **Authentication**: Basic login system for staff/admin

---

## 🗂️ Project Structure

Result-Management/
├── Task-1/
│ └── src/
│ ├── views/ (EJS templates)
│ ├── public/ (CSS, JS)
│ ├── routes/
│ └── server.js
├── Task-2/
│ └── layout.ejs
└── README.md

## 🚀 How to Run the Project Locally

### 1. Clone the Repository

```
git clone https://github.com/mohan-1705/Result-Management.git
cd Result-Management/Task-1/src
2. Install Dependencies
npm install
3. Start the Server
node server.js
Open your browser and navigate to: http://localhost:3000

🎯 Future Enhancements
Role-based access control (admin, teacher, student)

Student login for viewing results securely

PDF generation of marksheets

Performance analytics dashboard
