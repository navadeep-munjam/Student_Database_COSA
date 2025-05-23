<h1 align="center">📚 Welcome to the CoSA Student Database👋</h1>

<p align="center">
A comprehensive platform for managing student data within CoSA, including details about students' club memberships, positions of responsibility (PORs), and much more. This project offers efficient storage, retrieval, and management of student-related information, streamlining administrative tasks and enhancing overall efficiency.

</p>

<p align="center">
  <img src="https://img.shields.io/badge/Maintained%20By-OpenLake-green.svg" alt="Maintained by OpenLake">
  <img src="https://img.shields.io/badge/Maintainers-2-yellow.svg" alt="Contributors">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
</p>

---

## 🚀 Features

- **User-friendly Frontend**: Clean, responsive UI for easy access to student data.
- **Backend with MongoDB**: Secure and scalable backend using Node.js, Express, and MongoDB.
- **Search & Filter Functionality**: Quickly search, filter, and manage student data.
- **JWT-based Authentication**: Role-based authentication system for admins.
- **RESTful API**: RESTful endpoints for integration and automation.

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Axios, HTML5, CSS3
- **Backend**: Node.js, Express.js, JWT Authentication
- **Database**: MongoDB
- **Version Control**: Git and GitHub

---

## 🖥️ Setup Instructions

Follow these instructions to run the project locally.

### Prerequisites

Ensure that you have **Node.js** and **NPM** installed on your system.

### 1. Clone the Repository

```bash
git clone https://github.com/OpenLake/Student_Database_COSA.git
cd Student_Database_COSA
```

### 2. Backend Setup

- Navigate to the `Backend` directory:
  ```bash
  cd Backend
  ```
- Install the necessary packages:
  ```bash
  npm install
  ```
- Run the backend server:
  ```bash
  node index.js
  ```

### 3. Frontend Setup

- Navigate to the `frontend` directory:
  ```bash
  cd ../frontend
  ```
- Install the frontend dependencies:
  ```bash
  npm install
  ```
- Start the frontend server:
  ```bash
  npm start
  ```

Now, you should be able to access the frontend at `http://localhost:3000` and the backend at `http://localhost:5000`.

---

## 📂 Project Structure

```
Student_Database_COSA/
│
├── Backend/               # Node.js backend
│   ├── controllers/       # API route controllers
│   ├── models/            # Database models (MongoDB schemas)
│   ├── routes/            # API routes
│   ├── middleware/        # Authentication and role-based middleware
│   └── index.js           # Main server file
│
├── frontend/              # React.js frontend
│   ├── public/            # Public assets
│   └── src/               # Source code
│       ├── components/    # React components
│       ├── pages/         # Application pages
│       └── App.js         # Main App component
│
├── .gitignore             # Ignored files
├── README.md              # Project documentation
└── package.json           # Dependencies and scripts
```

---

## 🧑‍💻 Maintainers

This project is maintained by:

- [Nishant Verma](https://github.com/nishant9083)
- [Arbaz Shaikh](https://github.com/arbazshaikh150)

---

## 🤝 Contributing

We welcome contributions! Feel free to open an issue or submit a pull request. Before contributing, please make sure to:

1. Fork the repository.
2. Create a new branch.
3. Submit a pull request with your changes.

---

## 📧 Contact

If you have any questions or feedback, feel free to reach out to the maintainers.
