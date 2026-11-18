<p align="center">
  <img src="./assets/header.svg" alt="Nguyen Phat Tai — Software Engineering Profile" width="100%" />
</p>

Software Engineering student at FPT University (Can Tho), focused on Java backend development, relational database design, and software architecture.

My recent work centers on server-side web applications using Jakarta EE, Microsoft SQL Server, and containerized deployments with Docker. From this foundation, I am progressing toward Spring Boot, infrastructure engineering, and applied AI systems, with long-term research interest in analytical software and quantitative modeling.

<p align="center">
  <img src="./assets/rule.svg" alt="" width="100%" />
</p>

## Engineering Focus

- **01. Software Engineering** — Object-oriented design, layered application structure, and maintainable codebases.
- **02. Backend Systems** — Server-side web architecture, request handling, transactional workflows, and API design.
- **03. Database Engineering** — Relational schema modeling, T-SQL querying, and data integrity in SQL Server.
- **04. DevOps & Infrastructure** — Multi-stage container builds, Docker Compose environments, and reproducible deployments.
- **05. Artificial Intelligence** — Exploring applied AI systems and analytical software tooling. *(Ongoing study)*
- **06. Quantitative Research** — Studying predictive modeling, quantitative trading concepts, and data-driven decision systems. *(Research interest)*

<p align="center">
  <img src="./assets/rule.svg" alt="" width="100%" />
</p>

## Technology Stack

| Area | Used in Public Repositories | Currently Learning / Exploring |
| :--- | :--- | :--- |
| **Languages** | Java (JDK 11–21), T-SQL, HTML, CSS, JavaScript | Python |
| **Backend** | Jakarta EE 10 (Servlets, JSP), Apache Tomcat 10, JDBC, Apache POI | Spring Boot, REST APIs |
| **Databases** | Microsoft SQL Server 2022, Java File I/O Persistence | PostgreSQL, MySQL |
| **Infrastructure & Build** | Maven, Ant, Docker (multi-stage), Docker Compose, Git | Linux, Nginx, CI/CD |
| **AI & Research** | — | Machine Learning, Data Analysis, Quantitative Research |

<p align="center">
  <img src="./assets/rule.svg" alt="" width="100%" />
</p>

## Selected Projects

### [Ftech_learning_online](https://github.com/ngtaiphat1501/Ftech_learning_online)
`Java` · `Jakarta EE 10` · `Apache Tomcat 10` · `MS SQL Server` · `Maven` · `Docker`

- **Problem:** Build an end-to-end online learning and course commerce platform (free and paid courses) supporting learners, instructors, and administrators without relying on high-level application frameworks.
- **Contribution:** Fullstack Developer in a 5-member PRJ301 team project (FPT University Can Tho). Implemented the **Admin Dashboard**, **Cart & Checkout workflow** (coupon validation, VNPAY sandbox simulation, idempotent order creation), **Order History & Revenue Analytics** (Chart.js), and cross-module system integration.
- **Architecture & Implementation:** Structured as a Java Web MVC application packaged as a WAR via Maven, connecting to Microsoft SQL Server 2022 through `mssql-jdbc` and using Apache POI for Excel import/export. Containerized with a multi-stage `Dockerfile` (Maven + Temurin JDK 21 → Tomcat 10.1) and `docker-compose.yml` with SQL Server healthchecks.
- **Engineering Considerations:** Preventing duplicate orders during checkout via idempotent order generation, supporting environment-variable database overrides (`LEARNORA_DB_URL`), and aligning five independently developed modules onto a shared relational schema.
- **Status:** Completed academic capstone (updated November 2026) with setup guide, seed scripts, and Docker deployment configuration.

### [StudentManagementSystem](https://github.com/ngtaiphat1501/StudentManagementSystem)
`Java` · `Layered OOP` · `Ant` · `File Serialization`

- **Problem:** Manage student records, courses, enrollments, grades, extracurricular activities, and training scores in a lightweight console application without requiring an external database server.
- **Architecture & Implementation:** Organized into distinct Java layers — domain models (`Person`, `Student`, `User`, `Course`, `ClassEntity`, `Enrollment`, `Grade`, `Activity`, `TrainingScore`), interface-backed services (`AcademicService`, `ActivityService`, `FileService`, `ReportService`, `StudentService`), managers, role-based CLI menus (`Admin`, `Staff`, `Teacher`, `Student`), and validation utilities. Persists state in binary `.dat` files.
- **Engineering Considerations:** Maintaining separation between domain entities, business logic, and file serialization while enforcing role boundaries and input validation across four console user roles.
- **Status:** Completed academic team project (March 2026). Repository documentation (`README.md`) is not yet added.

<p align="center">
  <img src="./assets/rule.svg" alt="" width="100%" />
</p>

## Current Development

```text
Java Advanced Engineering  →  Spring Boot  →  DevOps & Infrastructure  →  AI Engineering
```

Ongoing work focuses on transitioning from Servlet/JSP architectures to **Spring Boot** and RESTful service design, expanding practical experience in **Linux** and **containerized deployment workflows**, and developing foundations for **AI-based analytical systems**, **predictive modeling**, and **data-driven decision systems**.

<p align="center">
  <img src="./assets/rule.svg" alt="" width="100%" />
</p>

## Contact

- **GitHub:** [github.com/ngtaiphat1501](https://github.com/ngtaiphat1501)
