# Spring_Boot_Application


# 🚀 Spring Boot Project Management Application (Jira Clone)

## 📋 Overview
This project is a comprehensive, Agile-focused task management backend system inspired by Jira. Built using **Java** and **Spring Boot**, it provides robust APIs for project tracking, sprint management, secure user authentication, team collaboration, and analytics. 

This repository is actively maintained by the backend development team, with strict adherence to Java Spring Boot best practices and Git repository integrity.

---

## 🛠️ Tech Stack
* **Language:** Java (JDK 17 / 25)
* **Framework:** Spring Boot 3.x
* **Security:** Spring Security & JWT (JSON Web Tokens)
* **Database:** Spring Data JPA / Hibernate (PostgreSQL / MySQL)
* **Storage:** AWS S3 / Local File System (for attachments)
* **Build Tool:** Maven
* **API Documentation:** Swagger / OpenAPI

---

## ✨ Core Features & Module Ownership

The system is divided into modular domains, developed collaboratively by the team:

| Module | Features | Owner |
| :--- | :--- | :--- |
| **User & Project Mgmt** | JWT Authentication, Role-based Access Control (RBAC), Project CRUD operations | **Raghav** |
| **Task & Workflow** | Ticket Creation/CRUD, Kanban Board Logic (To Do, In Progress, Done) | **Subhash** |
| **Collaboration** | Commenting System, Automated Notifications & Mentions | **Kiran** |
| **Agile & Search** | Sprint/Backlog Management, Advanced Search & Filtering | **Nandan** |
| **Storage & Analytics** | File Uploads/Attachments (S3/Local), Dashboard Stats & Workload Analytics | **Manohar** |

---

## 🚀 Getting Started

### Prerequisites
* Java Development Kit (JDK) installed and `JAVA_HOME` properly configured.
* Maven installed.
* A running instance of PostgreSQL/MySQL (Update `application.properties` with your credentials).

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/NANDANKUMAR14/Spring_Boot_Application.git
   cd project-management-app

2. Build the project: mvn clean install
3. Run the application: mvn spring-boot:run

##Team
Prasad - Final Code Reviewer & Project Assessor

Raghav - Authentication & Projects
Subhash - Tasks & Kanban
Kiran - Comments & Notifications
Nandan - Sprints & Advanced Search
Manohar - Attachments & Analytics

