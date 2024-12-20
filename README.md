# TaskMaster

**TaskMaster** is a full-stack task management application designed to help users organize and prioritize their daily tasks. It features a sleek, modern UI powered by React and a robust backend built with Node.js and Express, with MongoDB as the database.

---

## Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Setup and Installation](#setup-and-installation)
4. [Environment Variables](#environment-variables)
5. [Usage](#usage)
6. [Deployment](#deployment)
7. [Future Enhancements](#future-enhancements)
8. [Contributing](#contributing)
9. [License](#license)

---

## Features

- **User Authentication**: Secure sign-up, login, and logout using JWT.
- **Task Management**: Add, update, delete, and view tasks.
- **Task Prioritization**: Filter tasks by priority (Low, Medium, High).
- **Responsive Design**: Works seamlessly across devices.
- **Data Persistence**: All data is stored securely in MongoDB Atlas.
- **Search and Filters**: Quickly search and filter tasks to focus on what matters.

---

## Technologies Used

### Frontend
- **React**: For building the user interface.
- **React-Bootstrap**: For a sleek and responsive design.
- **Vite**: For fast development and build processes.

### Backend
- **Node.js**: Runtime environment.
- **Express.js**: For building the RESTful API.
- **MongoDB Atlas**: Cloud database for storing user data and tasks.

### Others
- **JWT**: For secure authentication.
- **dotenv**: For managing environment variables.
- **bcryptjs**: For password hashing.

---

## Setup and Installation

Follow these steps to run the app locally:

### Prerequisites
- Node.js (v16 or higher)
- MongoDB Atlas account
- Git installed

### Clone the Repository
```bash
git clone https://github.com/Abduls4u/TaskMaster.git
cd TaskMaster
```

### Backend Setup
- Navigate to the backend folder:
```bash
cd backend
```
- Install dependencies:
```bash
npm install
```
- Configure environment variables (see Environment Variables).
- Start the server:
```bash
npm run dev
```

### Frontend Setup
- Navigate to the frontend folder:
```bash
cd ../frontend
```
- Install dependencies:
```bash
npm install
```
- Start the development server:
```bash
npm run dev
```

### Environment Variables
- Create a .env file in the backend directory with the following keys:
```bash
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@<cluster-name>.mongodb.net/<database-name>?retryWrites=true&w=majority
JWT_SECRET=<your-secret-key>
```
Replace placeholders with your MongoDB credentials and a strong secret key.

### Usage
- Open the frontend app in your browser (usually http://localhost:5173 during development).
- Register or log in to access the dashboard.
- Add, edit, or delete tasks and filter them by priority.
- Logout securely when done

### Deployment
#### Frontend Deployment
Deployed [here](https://taskmaster-9558.onrender.com)

#### Backend Deployment
Hosted [here](https://taskmasterapi-ca20.onrender.com/)
Ensure the frontend is configured to communicate with the live backend API by setting the VITE_API_URL environment variable in the frontend.

### Future Enhancements
- Notifications: Add reminders for task deadlines.
- User Profiles: Allow users to customize their profiles.
- Dark Mode: Add support for dark mode.
- Real-Time Updates: Use WebSockets for live task updates.
- Contributing
- We welcome contributions! Please fork the repository and submit a pull request with your changes.

### Contributing
- Steps to Contribute:
```bash
# Fork the repository.
# Create a new branch:
git checkout -b feature-name.
# Commit your changes:
git commit -m "Add some feature".
# Push the branch: git push origin feature-name.
```
Open a pull request on GitHub.

### License
This project is licensed under the MIT License.

### Contact
For any questions or suggestions, please reach out at:
- **Developer:** Abdulsalam Abdulsomad .A.
- **Email:** [Send Email](mailto:abdulsalamabdulsomad14@gmail.com)
- **X:** [@abduls0mad](https://x.com/abduls0mad)
- **GitHub:** [abduls4u](https://github.com/abduls4u)
