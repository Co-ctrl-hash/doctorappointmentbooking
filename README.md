# 💕 Doctor Booking Platform

A full-stack doctor appointment platform built with the **MERN** stack, enabling users to book appointments, consult doctors through real-time video calls, and securely manage their medical profiles and documents.

## 🚀 Features

* 🗓️ **Appointment Scheduling** – Effortless booking flow between patients and doctors.
* 🔐 **Authentication & Authorization** – Secure login system with JWT and bcrypt, supporting role-based access (Admin, Doctor, Patient).
* 📹 **Real-time Video Consultations** – Low-latency video calling using WebRTC and Socket.IO.
* 💳 **Stripe Integration** – Secure online payments for booking consultations.
* 🧑‍⚕️ **Doctor Dashboard** – Manage availability, appointments, and patient details.
* 📁 **Cloudinary Integration** – Upload and store profile pictures and medical documents.
* 📦 **RESTful API** – Backend services built with Express.js for scalability and performance.

---

## 🛠️ Tech Stack

| Frontend | Backend             | Database | Real-Time         | Auth        | Payment | Storage    |
| -------- | ------------------- | -------- | ----------------- | ----------- | ------- | ---------- |
| React.js | Node.js, Express.js | MongoDB  | WebRTC, Socket.IO | JWT, bcrypt | Stripe  | Cloudinary |

---

## 🌐 Live Demo

[🔗 Live Application]https://doctorappointmentbooking-m1os.onrender.com/
[📁 GitHub Repository](https://github.com/Co-ctrl-hash/doctorappointmentbooking)



## 📁 Folder Structure

```
doctor-booking-platform/
│
├── client/               # Frontend (React)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── ...
│   └── ...
│
├── server/               # Backend (Node.js + Express)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── ...
│
├── .env
├── package.json
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone git@github.com:Co-ctrl-hash/doctorappointmentbooking.git
cd doctorappointmentbooking

```

### 2. Backend Setup

```bash
cd server
npm install
```

Create a `.env` file in the `server` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

Start the backend server:

```bash
npm run dev
```

### 3. Frontend Setup

```bash
cd ../client
npm install
npm run dev
```

---

## 🛡️ Security

* Passwords are securely hashed with `bcrypt`.
* Session management and route protection with `JWT`.
* HTTPS recommended for production deployments.
* Input validation on both frontend and backend.

---

## 💡 Future Enhancements

* 🧪 Add video consultation history and prescriptions.
* 🗕️ Sync doctor calendars with Google Calendar.
* 📨 Email/SMS notifications for appointment reminders.
* 📒 Admin analytics dashboard.

---

## 🤝 Contributing

Contributions are welcome!
If you find a bug or want to contribute a feature, feel free to fork the repo and submit a pull request.



---

## 👤 Authors

**Harsh Deep**
📧 [btech10920.22@bitmesra.ac.in](mailto:btech10920.22@bitmesra.ac.in)
🔗 [LinkedIn](https://www.linkedin.com/in/harsh-deep-a2b104264/)
🐙 [GitHub](https://github.com/Co-ctrl-hash)

---

> Made with ❤️ using the MERN stack.
