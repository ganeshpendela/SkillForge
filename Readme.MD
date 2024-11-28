# SkillForge

SkillForge is a course management system that supports role-based access for Admins and Employees. Admins manage courses, users, modules, quizzes, discussions, announcements, and concerns. Employees interact with assigned courses, participate in discussions, attempt quizzes, and post concerns.

## Table of Contents
1. [Frontend](#frontend)
2. [Backend](#backend)
3. [Setup](#setup)
4. [APIs](#apis)

---

## Frontend

The frontend is a React-based application. It provides separate dashboards for Admin and Employee roles.

### Key Features
- **Admin**: Manage users, courses, modules, discussions, quizzes, and concerns.
- **Employee**: View assigned courses, participate in discussions, take quizzes, and raise concerns.

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SkillForge-Frontend.git

2. Install dependencies:
    ```bash
    cd SkillForge-Frontend
    npm install

3. Run the app:
    ```bash
    npm run dev

## Backend

The backend is built using Spring Boot. It manages data, handles API requests, and enforces business logic.

### Key Features
- **Admin**: Create, update, delete courses, assign users, manage discussions and quizzes.
- **Employee**: Access courses, participate in quizzes and discussions, and raise concerns.

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SkillForge-Backend.git

2. Install dependencies:
    ```bash
    cd SkillForge-Backend
    mvn clean install

3. Run the app:
    ```bash
    mvn spring-boot:run

## API's
The backend exposes various RESTful APIs for course, user, module, quiz, discussion, and concern management.
For the complete list of available APIs, refer to the documentation in the backend repository.
