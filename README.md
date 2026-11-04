# Employee Management App

A Flutter-based Employee Management Application built with **GetX, REST API, Repository Pattern, and JWT Authentication**. This application allows users to manage employees and browse products through a clean and responsive interface.

## 🌐 Live Demo

**Application:** https://chetra-employee-app-2026.web.app

**Backend API:** https://employee-management-app-d8tt.onrender.com

## ✨ Features

### Authentication
- User Login and Logout
- JWT-based authentication using DummyJSON API
- Local session storage using GetStorage

### Employee Management
- Display all employees
- Add new employees
- Update employee information
- Delete employees
- Form validation
- Loading and error handling

### Product Management
- Display product lists
- View product information
- Add new products
- Update products
- Delete products

### User Interface
- Responsive Flutter Web UI
- Clean and organized layout
- Loading indicators
- Error messages and notifications

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Flutter | Frontend Framework |
| Dart | Programming Language |
| GetX | State Management and Navigation |
| Dio | HTTP Client |
| GetStorage | Local Storage |
| REST API | Backend Communication |
| JSON Server | Mock REST API |
| DummyJSON | Authentication API |
| Render | Backend Hosting |
| Firebase Hosting | Web Deployment |
| Git & GitHub | Version Control |

## 🏗️ Project Architecture

The project follows the **Repository Pattern** to separate business logic, API communication, and UI components.

```text
lib/
├── app/
│   ├── bindings/
│   ├── routes/
│   └── core/
│       ├── constants/
│       ├── services/
│       └── storage/
│
├── data/
│   ├── models/
│   └── repositories/
│
├── controllers/
│
├── presentation/
│   ├── login/
│   ├── home/
│   ├── employees/
│   └── products/
│
└── main.dart

api/
├── db.json
├── package.json
├── package-lock.json
└── server.js
```

## 🔗 API Endpoints

### Employee API

| Method | Endpoint | Description |
|---|---|---|
| GET | `/employees` | Get all employees |
| POST | `/employees` | Add employee |
| PUT | `/employees/:id` | Update employee |
| DELETE | `/employees/:id` | Delete employee |

### Product API

| Method | Endpoint | Description |
|---|---|---|
| GET | `/products` | Get all products |
| POST | `/products` | Add product |
| PUT | `/products/:id` | Update product |
| DELETE | `/products/:id` | Delete product |

### Authentication API

```text
POST https://dummyjson.com/auth/login
```

## 🚀 Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/kheangphearun/employee-management-app.git
```

### 2. Navigate to Project

```bash
cd employee-management-app
```

### 3. Install Flutter Dependencies

```bash
flutter pub get
```

### 4. Run the Application

```bash
flutter run -d chrome
```

### 5. Run Backend Locally (Optional)

Open another terminal:

```bash
cd api
npm install
npm start
```

The local API will run at:

```text
http://localhost:3000
```

## 🌍 Deployment

- **Frontend:** Firebase Hosting
- **Backend:** Render Web Service
- **Repository:** GitHub

The application uses cloud-hosted services so users can access the deployed web application without running the project locally.

## 👨‍💻 Developer

**KHEANG PHEARUN**

- GitHub: https://github.com/kheangphearun
- Repository: https://github.com/kheangphearun/employee-management-app

---

**Built with Flutter & Dart.**

**Developed by Kheang Phearun.**