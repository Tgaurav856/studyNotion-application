# 📚 Study Notion - A Learning Management System (LMS)

Study Notion is a full-stack **Learning Management System (LMS)** built using **Node.js, Express.js, MongoDB**, and integrates authentication, course management, and user roles (Admin, Instructor, and Students).

## 🚀 Features
- 🔐 **User Authentication** (JWT & bcrypt)
- 🏫 **Role-based Access** (Admin, Instructor, Student)
- 📚 **Course Creation & Enrollment**
- 🎥 **Video Upload & Storage** (Cloudinary Integration)
- 💳 **Payment Integration** (Stripe/Razorpay)
- 🌐 **RESTful API for Frontend Integration**
- 📄 **Markdown-based Blog System**
- 📊 **Dashboard for Instructors & Admins**

---

## 🛠 Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose ORM
- **Authentication:** JWT, bcrypt.js
- **File Uploads:** Multer & Cloudinary
- **Payment Gateway:** Stripe/Razorpay
- **API Documentation:** Swagger/Postman
- **Frontend (Optional):** React.js (if applicable)

---



 1️⃣ Clone the Repository  
```sh
git clone https://github.com/yourusername/study-notion.git
cd study-notion
2️⃣ Install Dependencies
sh
Copy
Edit
npm install
3️⃣ Set Up Environment Variables
Create a .env file in the root and add:

sh
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret
STRIPE_SECRET_KEY=your_stripe_key
4️⃣ Run the Server
sh
Copy
Edit
npm start


