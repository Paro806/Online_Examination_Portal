# Online Examination Portal (MERN Stack)

A **full-stack Online Examination Portal** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)** designed to securely conduct online exams with role-based access for **Admin and Students**.
The platform supports exam creation, secure authentication, online exam participation, automated evaluation, and result publication.

This project demonstrates practical implementation of **full-stack development, REST API architecture, secure authentication, database management, and modern frontend design**.

---

##  Key Features

### Admin Panel

* Secure admin authentication
* Create, update, and manage exams
* Add/edit exam questions
* Evaluate student submissions
* Publish results and grades

### Student Panel

* Student registration and login
* View available exams
* Attempt online exams
* Submit answers securely
* View results and performance

###  Security Features

* JWT-based authentication
* Role-based authorization (Admin / Student)
* Protected backend APIs
* Environment variable security configuration

---

## 🛠 Tech Stack

### Frontend

* React.js
* HTML5, CSS3, JavaScript
* React Router DOM
* Axios for API communication

### Backend

* Node.js
* Express.js
* REST API architecture

### Database

* MongoDB Atlas (Cloud Database)
* Mongoose ODM

### Authentication & Security

* JWT Authentication
* Middleware authorization
* Protected routes

---

##  Project Structure

```
Exam-Portal/
│
├── BackEnd/
│   ├── controller/
│   ├── middleware/
│   ├── model/
│   ├── routes/
│   ├── index.js
│   └── .env
│
├── FrontEnd/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── services/
│   │   ├── styles/
│   │   └── App.js
│
└── README.md
```

---

##  Installation

### Clone Repository

```bash
git clone https://github.com/Paro806/online-examination-portal.git
cd online-examination-portal
```

### Backend Setup

```bash
cd BackEnd
npm install
```

Create `.env` file:

```
PORT=5000
MONGO_URI=mongodb://localhost:27017/exam_portal
JWT_SECRET=your_jwt_secret_key_change_this_in_production
```

Run backend:

```bash
npm start
```

### Frontend Setup

```bash
cd FrontEnd
npm install
npm start
```

---

## Usage

* Admin logs in to create/manage exams and publish results
* Students register/login to attempt exams
* Exams are evaluated and results displayed securely

---

##  Configuration

Key configuration variables:

* **MONGO_URI** → MongoDB Atlas connection string
* **JWT_SECRET** → Authentication secret key
* **PORT** → Backend server port

---

##  ATS-Friendly Skills Demonstrated

* Full-stack MERN development
* RESTful API design and integration
* JWT authentication and role-based authorization
* MongoDB database modeling and cloud integration
* React frontend architecture and routing
* Secure web application development
* Deployment-ready project structuring

---

##  Future Enhancements

* Timer-based auto submission
* Anti-cheating/proctoring system
* Exam analytics dashboard
* Email/OTP verification system
* Deployment pipeline (CI/CD)

---

##  Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open pull request
