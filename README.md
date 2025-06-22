# 📝 Online Exam Portal

A Java-based web application that allows administrators to manage online quizzes and students to take exams. Built using JSP, Servlets, JDBC, and MySQL. This project follows MVC architecture and includes user authentication, session management, and admin features.

---

## 🔧 Technologies Used

- **Java (Servlets + JSP)**
- **Apache Tomcat 9**
- **MySQL Database**
- **JDBC**
- **HTML / CSS**
- **Eclipse IDE**

---

## 📁 Project Structure
OnlineExamPortal/
├── WebContent/
│ ├── login.jsp
│ ├── admin.jsp
│ ├── add_question.jsp
│ └── other JSPs...
├── src/
│ ├── com.servlet/
│ │ ├── LoginServlet.java
│ │ └── AddQuestionServlet.java
│ ├── com.util/
│ │ └── DBUtil.java
│ └── com.model/
│ └── Question.java (if applicable)
├── build/
└── README.md

---

## 🛠️ Features

### 👨‍🎓 Student
- Login to exam portal
- Take online exams (MCQs)
- View final score

### 👨‍💼 Admin
- Login with session-based authentication
- Add new questions to the database
- Manage question bank

---

## 🚀 How to Run

1. **Clone or download the project**:
   ```bash
   git clone https://github.com/your-username/OnlineExamPortal.git

 
2. Import into Eclipse:

    File → Import → Existing Projects into Workspace
    Select the project folder

3. Set up database:

    Create a MySQL database (e.g., exam_portal)
    Import the provided schema.sql (if available)
    Update DBUtil.java with your MySQL credentials

4. Run on Tomcat:

    Right-click project → Run on Server → Choose Apache Tomcat

5. Access in browser:

    http://localhost:8080/OnlineExamPortal/


🔐 Admin Credentials
Default credentials (if not connected to real user table):

  Username: admin
Password: admin123  

 Future Enhancements
Add student registration & profile

Timer-based exam interface

Results history & analytics

REST API for mobile app integration

🙌 Acknowledgements
Created as part of academic coursework at Adani University
Guided by: Prof. Bhagyesh Patel

📄 License
This project is licensed under the MIT License. Feel free to use and modify it.

---

Let me know if you'd like me to include your GitHub profile link, portfolio link, or add a screenshot section to the README as well. ✅
