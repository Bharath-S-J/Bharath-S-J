# Hi 👋, I'm Bharath S J

I love solving hard technical problems, especially where performance, scalability, and automation intersect. My projects range from real-time apps and microservice systems to custom CLI that generate APIs from a schema in seconds.

Explore my **[portfolio](https://bharathsj.com/)** for full-stack projects built with Node.js, MongoDB, React, Java, Python, and more — all driven by clean architecture and practical design.

---

## 🌐 Connect with Me  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/bharathsj)  [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:bharath@bharathsj.com)  [![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?logo=vercel&logoColor=white)](https://bharathsj.com/)

---

## 🛠️ Technologies & Tools

### Programming Languages  
![C](https://img.shields.io/badge/c-%2300599C.svg?style=plastic&logo=c&logoColor=white)  ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=plastic&logo=c%2B%2B&logoColor=white)  ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=plastic&logo=openjdk&logoColor=white)  ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=plastic&logo=javascript&logoColor=%23F7DF1E)  ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=plastic&logo=typescript&logoColor=white)  ![Python](https://img.shields.io/badge/python-3670A0?style=plastic&logo=python&logoColor=ffdd54)  ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=plastic&logo=php&logoColor=white)

### Web Development  
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=plastic&logo=html5&logoColor=white)  ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=plastic&logo=css3&logoColor=white)  ![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=plastic&logo=angular&logoColor=white)  ![React](https://img.shields.io/badge/react-%2320232a.svg?style=plastic&logo=react&logoColor=%2361DAFB)  ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=plastic&logo=jquery&logoColor=white)

### Backend & Frameworks  
![Spring Boot](https://img.shields.io/badge/spring-%236DB33F.svg?style=plastic&logo=spring&logoColor=white)  ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=plastic&logo=node.js&logoColor=white)  ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=plastic&logo=express&logoColor=%2361DAFB)

### Databases & Cloud  
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=plastic&logo=mongodb&logoColor=white)  ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=plastic&logo=mysql&logoColor=white)  ![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=plastic&logo=postgresql&logoColor=white)  ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=plastic&logo=firebase)  ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=plastic&logo=amazonaws&logoColor=white)

### DevOps & Tools  
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=plastic&logo=git&logoColor=white)  ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=plastic&logo=github&logoColor=white)  ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=plastic&logo=docker&logoColor=white)  ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=plastic&logo=jenkins&logoColor=white)  ![CI/CD](https://img.shields.io/badge/CI%2FCD-%23008CBA.svg?style=plastic&logo=githubactions&logoColor=white) 
![Terraform](https://img.shields.io/badge/Terraform-%23624BFF.svg?style=plastic&logo=terraform&logoColor=white)

---

## 💻 Project Showcase

Explore a selection of my key projects demonstrating full-stack development, system design, and scalable architectures.

---

### ⚡ cfapi – Code-Free API Generator

[GitHub Repo](https://github.com/Bharath-S-J/cfapi) | [NPM Package](https://www.npmjs.com/package/@bharathsj/cfapi)

A blazing-fast CLI tool to **scaffold full REST APIs** from just a simple schema. Supports **mock JSON** or **MongoDB (Mongoose)** engines, generating everything from routes, models, and controllers to OpenAPI docs — all without writing a single line of boilerplate.

**Key Features:**

* 📁 Generates folder structure, controllers, routes, and models automatically
* ✅ Built-in input validation and OpenAPI schema generation
* 🧪 Supports mock storage (`.json`) with auto-generated fake data
* 🧬 Full Mongoose support for MongoDB, including nested schemas and refs
* ✏️ PATCH (flat updates), PUT (full replaces), and input sanitization
* ⚙️ CLI support for `generate` and `add` commands
* 💡 Simple schema format with types like string, number, uuid, email, object, array, etc.
* 🔁 OpenAPI-compliant output for easy integration and docs

📦 Install:
```bash
npm install -g @bharathsj/cfapi
```
📂 Example command:
```bash
cfapi generate --schema user.schema.json --engine mock --output ./generated-api
```
⚠️ Note: Designed for quick scaffolding and prototyping — not a replacement for full custom-built backends.

---

### 💬 Intent Chat – AI-Enhanced Real-Time Chat Application  
[GitHub Repo](https://github.com/Bharath-S-J/Intent-Chat)  

A full-stack real-time chat app with email/password authentication, contact invitations, AI-powered messaging features, real-time text/image messaging, online presence, and theme customization. Built using **React**, **Node.js**, **MongoDB**, **Socket.IO**, **Cloudinary**, and **OpenAI** (via OpenRouter).  

**Key Features:**  
- JWT Authentication & protected routes  
- AI-powered tone detection (😄/😢/😠) and smart reply suggestions  
- Mutual contact-based messaging system  
- Image upload with Cloudinary integration  
- Real-time messaging and notifications with Socket.IO  
- Zustand state management and React Router v7  
- Email invites and profile management  
- Theme customization (light/dark modes)  

---

### 🏦 Total Bank Manager – Banking Management System  
[GitHub Repo](https://github.com/Bharath-S-J/Total-Bank-Manager)

A desktop banking app with **Java (Swing)** and **MySQL** supporting a three-tier user access model (Customer, Employee, Manager). Features graphical stats, email verification, transaction history, and complaint management.

**Key Features:**  
- Role-based access (Customer, Employee, Manager)  
- Bar & line chart statistics  
- Email verification and notifications  
- PDF export of transactions  
- Automated account creation and complaint tracking  

---

### ☕ Spring Boot Microservices Architecture  
[GitHub Repo](https://github.com/Bharath-S-J/SpringBootMicroservices)

A microservices-based system using **Spring Boot** with decoupled services, inter-service communication, and monitoring. Angular frontend with Kafka messaging and Keycloak security.

**Tech Stack:**  
- Spring Boot, Angular, MongoDB, MySQL  
- Kafka event streaming  
- API Gateway via Spring Cloud  
- Grafana for monitoring  
- Keycloak authentication  

---

### ✅ Task Master – Task Management Web App  
[GitHub Repo](https://github.com/Bharath-S-J/Task-Master-fullstack) | [Live Demo](https://task-master-jade-beta.vercel.app/)

Responsive task manager built with **React**, **Firebase**, and **Vite** featuring authentication, real-time sync, notifications, and minimal UI.

> ℹ️ **Note**: All core features work in the live demo. However, the **email reminder** functionality requires a backend server and is currently unavailable in this version.

**Key Features:**  
- Email and Google OAuth authentication  
- Add, edit, delete, and track task completion  
- Real-time syncing with Firebase  
- Email verification and password recovery  
- Mobile responsive and minimal design  
- Email & audio alerts  

---

### 💰 Finance Flow – Loan & EMI Management Desktop App  
[GitHub Repo](https://github.com/Bharath-S-J/Finance-Flow)

Desktop app built with **Python** and **MySQL** for loan management, EMI planning, user roles, payment tracking, and document uploads.

**Key Features:**  
- Role-based user management  
- EMI and loan calculations  
- Payment & penalty tracking  
- Secure document upload and preview  
- Financial reports  

---

### 🛒 Virtual Agri-Marketplace – Farmer-Buyer Platform  
[GitHub Repo](https://github.com/Bharath-S-J/Virtual-Agri-Marketplace)

Full-stack web platform connecting farmers and buyers with inventory, shopping cart, and order tracking features.

**Key Features:**  
- Authentication & role-based access  
- Product & inventory management  
- Real-time stock updates and order processing  

---

### 📚 Digital Due Records – Store Management System  
[GitHub Repo](https://github.com/Bharath-S-J/Digital-Due-Records)

A lightweight C-based ledger system for small businesses to track customer dues and generate bills.

**Key Features:**  
- Dual access (Customer & Admin)  
- Customer records and bill generation  
- Search functionality and password protection  

---
### 📝 Node Blog Website  
[GitHub Repo](https://github.com/Bharath-S-J/NodePress)

A full-featured blog website built with **Node.js**, **Express**, and **MongoDB**, featuring user authentication, CRUD operations for posts, and comments system.

**Key Features:**  
- User signup/login with hashed passwords  
- Create, edit, delete blog posts  
- Commenting system with moderation  
- RESTful API architecture  
- Responsive design and clean UI

---


### 📚 Digital Due Records – Store Management System
[GitHub Repo](https://github.com/Bharath-S-J/Digital-Due-Records)

A lightweight store ledger system built in **C**, designed to streamline customer due tracking and bill generation for small businesses.

🔹 **Key Features:**

* 🔒 **Dual Access System** (Customer & Admin)
* 📝 **Customer Record Management**
* 🧾 **Bill Generation & Search Functions**
* 🛡️ **Password Protection & Recovery**

---


### 🌐 Personal Portfolio Website  
[GitHub Repo](https://github.com/Bharath-S-J/Portfolio) | [Live Demo](https://bharathsj.com/)

Modern, responsive portfolio site showcasing your projects, skills, and resume, with a clean aesthetic and dark mode toggle.

**Key Features:**  
- React-based SPA  
- Dark/light mode support  
- Project showcases with links and descriptions  
- Contact form integration  

---

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=Bharath-S-J&shadow_green&hide_border=true&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=Bharath-S-J&themeshadow_green&hide_border=true)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Bharath-S-J&tshadow_green&hide_border=true&include_all_commits=false&count_private=false&layout=compact)
