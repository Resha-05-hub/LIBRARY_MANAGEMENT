# 📚 Library Management System (Java Servlet & JDBC)

A simple **Library Management System** developed using **Java Servlets, JDBC, HTML**, and **Oracle Database**.
This project allows users to **add books, view books, and manage author details** through a web-based interface.

---

## 🚀 Features

* Add new books
* View available books
* Author management
* Input validation
* JDBC database connectivity
* MVC architecture (Servlets, DAO, Beans)

---

## 🛠️ Tech Stack

| Layer    | Technology      |
| -------- | --------------- |
| Backend  | Java, Servlets  |
| Frontend | HTML            |
| Database | Oracle Database |
| Server   | Apache Tomcat 9 |
| IDE      | Eclipse         |
| Driver   | ojdbc17.jar     |

---

## 📁 Project Structure

```
LibraryManagement/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── wipro/
│       │           └── book/
│       │               ├── bean/
│       │               │   ├── AuthorBean.java
│       │               │   └── BookBean.java
│       │               ├── dao/
│       │               │   ├── AuthorDAO.java
│       │               │   └── BookDAO.java
│       │               ├── service/
│       │               │   └── Administrator.java
│       │               ├── servlets/
│       │               │   ├── MainServlet.java
│       │               │   └── ViewServlet.java
│       │               └── util/
│       │                   └── DBUtil.java
│       └── webapp/
│           ├── AddBook.html
│           ├── ViewBook.html
│           ├── Menu.html
│           ├── Invalid.html
│           ├── Failure.html
│           └── WEB-INF/
│               └── lib/
│                   └── ojdbc17.jar
```

---

## ▶️ How to Run the Project

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/LibraryManagement.git
   ```
2. Import the project into **Eclipse** as a **Dynamic Web Project**
3. Add **Apache Tomcat 9** server
4. Add **ojdbc17.jar** inside `WEB-INF/lib`
5. Execute SQL queries in **Oracle Database**
6. Start the **Tomcat server**
7. Open the browser and navigate to:

```
http://localhost:8080/LibraryManagement/Menu.html
```

---

## 🖼️ Project Screenshots

<img width="1257" height="522" alt="Screenshot 1" src="https://github.com/user-attachments/assets/c2e536dd-3c5b-4219-90c2-b3ab7b51a36b" />

<img width="1281" height="696" alt="Screenshot 2" src="https://github.com/user-attachments/assets/cdc0b4a1-2fda-462d-abd2-dc5947f84514" />

<img width="1413" height="603" alt="Screenshot 3" src="https://github.com/user-attachments/assets/704c348d-2cae-4286-b5c5-d1478b0fea94" />

<img width="1310" height="537" alt="Screenshot 4" src="https://github.com/user-attachments/assets/54ec668c-40b1-4dda-afb1-942878276b35" />

---

## ❌ Error Handling Pages

* **Invalid.html** – Incorrect input
* **Failure.html** – Operation failure

---

## 👩‍💻 Author

**RASMI RESHA A**
Java | JDBC | Servlets
