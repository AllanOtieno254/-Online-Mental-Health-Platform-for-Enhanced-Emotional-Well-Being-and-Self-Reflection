# 🌿 Online-Mental-Health-Platform-for-Enhanced-Emotional-Well-Being-and-Self-Reflection-

A secure, user-focused journaling web application built using **Node.js**, **Express.js**, and **MongoDB**. The platform encourages emotional self-reflection, mood tracking, and self-care, particularly for youth and young adults. This system prioritizes **privacy**, **security**, and **accessibility**.

# 🌿 user interface outlook


https://github.com/user-attachments/assets/020498f2-0405-4595-9e08-1a40622d8ad0


# 🌿 admin interface outlook:



https://github.com/user-attachments/assets/24114650-fa4c-4b1f-bbb5-fd1d3ad806f8


---

## 🔍 Project Description

This platform serves as a mental health and journaling system allowing users to log their thoughts, track moods, and reflect on their emotional well-being. It is developed with a focus on data protection, ethical design, and accessibility.

---

## 🚀 Features

- 📝 Secure personal journaling with date and mood tagging  
- 🔒 Role-based dashboard protection (Admin/User)  
- ✅ Consent-based onboarding with Terms & Conditions checkbox  
- 🪠 Visualization of journal history and emotional trends (planned)  
- 👨‍⚖️ Admin control panel to monitor system usage  
- 🧹 Modular backend architecture using MVC  
- 🌐 MongoDB Atlas cloud-based database  

---

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (MongoDB Atlas)
- **Authentication:** JWT (JSON Web Tokens), bcrypt
- **Testing:** Manual and security checks (Protected routes, Password strength)
- **Dev Tools:** MongoDB Compass, Postman, VS Code

---

## 🏠 System Architecture

```plaintext
Frontend (Journaling UI) --> Express API Server --> MongoDB Atlas
                             |
                          Middleware (JWT, Auth Checks)
                             |
                          Controllers (Logic Handling)
```

---

## 📁 File Structure

```plaintext
mental-health-reflection-platform/
├── client/              # Frontend UI files
├── server/              # Backend logic
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   ├── routes/
│   ├── config/
│   └── server.js
├── .env
├── .gitignore
├── README.md
├── package.json
└── LICENSE
```

---

## 🛠️ Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AllanOtieno254/mental-health-reflection-platform.git
   cd mental-health-reflection-platform
   ```

2. **Install backend dependencies:**
   ```bash
   cd server
   npm install
   ```

3. **Add environment variables in `.env`:**
   ```bash
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```

4. **Start the server:**
   ```bash
   npm start
   ```

5. **Access MongoDB Atlas or Compass to monitor your database**

---

## 🔧 How the System Handles Data

- Uses **MongoDB** as a NoSQL database, which is resilient to SQL injection.
- Passwords are **hashed** before storage using `bcrypt`.
- **Protected routes**: You cannot access the dashboard without logging in.
- Strong password policies implemented during signup.
- Uses **Express.js** to create API endpoints that communicate securely with MongoDB using the connection URI. Data is visualized via Atlas or Compass.

---

## 🔐 How the Backend Manages User Data

- **Routes folder**: Defines route access (e.g., `/admin` for admin panel).
- **Controllers folder**: Contains the logic for user authentication, data manipulation, and journaling.
- **Middleware folder**: Protects routes using JWT tokens and role-based logic.
- **Role restriction**: If not an admin, you cannot access protected dashboard areas.

---

## 📈 Data Privacy & Ethical Considerations

- All data is stored in a secure cloud-based environment.
- Only authenticated users can access their journals.
- JWT tokens ensure secure session validation.
- **Consent required**: Users must check a box agreeing to the platform’s terms before proceeding.
- Clear ethical boundary: Data is not shared with third parties.

---

## 🏥 Healthcare Guidelines

- The system is managed by an **admin** role.
- Admins can oversee the journaling environment and ensure healthy practices.
- Though it is not a clinical tool, it is built with care and privacy in mind, aligning with general mental health tech standards.

---

## 🖼️ Screenshots

##  User interface

![journal](https://github.com/user-attachments/assets/53c4f4ef-d540-4862-8849-a624656ec145)
![dashboard](https://github.com/user-attachments/assets/48dc0957-d7dc-49c7-b007-0361d9d229c7)
![crisis resources](https://github.com/user-attachments/assets/3a2af3a1-3ab0-44a4-9082-387297e14f45)
![community](https://github.com/user-attachments/assets/c65ec090-9015-459d-a760-c3f73349520b)
![therapist](https://github.com/user-attachments/assets/4bf5f73a-c78c-4da6-9a37-03526b26f1d7)
![resources](https://github.com/user-attachments/assets/7735d5a8-a074-4cea-9676-446f2a53c150)
![mood tracker](https://github.com/user-attachments/assets/af5720e9-bd86-4afd-bf54-9a58d331f75f)


##  Admin interface

![admin](https://github.com/user-attachments/assets/0da5f832-4393-4809-b17b-ea3787448fb1)

## 📚 Topics Covered

- Secure user authentication
- RESTful API design with Express.js
- MongoDB schema modeling
- Middleware and route protection
- Role-based access control
- Environment configuration (.env)
- Cloud-based NoSQL database (MongoDB Atlas)
- Frontend and backend integration
- Journaling and emotional intelligence
- Data ethics in mental health platforms

---

## 🌱 Future Improvements

- Sentiment analysis using Natural Language Processing (NLP)
- Mood graphs and emotional trends using Chart.js or D3.js
- Counseling chatbot integration
- Push notifications for journaling reminders
- Mobile-friendly PWA version
- More granular role privileges (e.g., Moderators)

---

## 📚 License

This project is licensed under the **MIT License**. Feel free to fork, adapt, and use with attribution.

---

## 🌟 Author

**Allan Otieno Akumu**  
Student of Computer Science, Zetech University  
GitHub: [AllanOtieno254](https://github.com/AllanOtieno254)

---

## 🌍 GitHub Topics

```
mental-health
journaling
nodejs
expressjs
mongodb
emotion-tracking
self-care
data-privacy
jwt-auth
secure-app
```

---
