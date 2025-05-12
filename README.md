<<<<<<< HEAD
# memory-game-1
=======
﻿# 🧩 Memory Challenge - Java Web Game

![Java](https://img.shields.io/badge/Java-17+-orange)
![Servlet](https://img.shields.io/badge/Jakarta_Servlet-5.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)

<div align="center">
  <img src="https://i.imgur.com/JQh6WYl.png" width="400" alt="Game Preview">
</div>

## 🧠 Overview

Memory Challenge is a simple Java-based web application that puts your concentration and memory to the test! Flip cards, remember their positions, and try to match all the pairs.

---

## ✨ Key Features
- Interactive and responsive card grid
- Smooth flip animations
- Game state stored using server-side sessions
- Works on desktop and mobile browsers

---

## 🛠 Tech Stack

| Layer          | Technology Used       |
|----------------|-----------------------|
| Backend        | Java (Servlets API)   |
| Frontend       | JSP + HTML5/CSS3      |
| State Handling | HTTP Sessions         |
| Build System   | Maven                 |

---

## 📦 Installation Guide

### 🔧 Prerequisites
- Java Development Kit (JDK) 17+
- Apache Tomcat Server 10+
- Maven 3.8+

### ▶️ Run the Project
Clone the repository and run the app locally using Maven:
```bash
mvn tomcat7:run
MemoryGame/
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── memorygame/
│       │           ├── controllers/
│       │           │   ├── GameServlet.java
│       │           │   └── InitServlet.java
│       │           └── models/
│       │               └── Card.java
│       └── webapp/
│           ├── WEB-INF/
│           │   ├── web.xml
│           │   └── lib/
│           ├── assets/
│           │   ├── css/
│           │   │   └── memory.css
│           │   └── img/
│           │       ├── card_1.png ... card_8.png
│           │       └── back.png
│           ├── game/
│           │   ├── board.jsp
│           │   └── end.jsp
│           └── index.jsp
└── pom.xml
>>>>>>> cf189af (Add my file)
