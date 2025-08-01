# Job Manager

Job Manager is a full-stack web application for managing job applications. It allows users to register, log in, and track their job applications, including company, position, and status. The project is split into a React frontend and a Node.js/Express backend, with MongoDB as the database.

## Features

- **User Authentication:** Register and log in securely with JWT-based authentication.
- **Job Management:** Create, view, update, and delete job applications.
- **Status Tracking:** Track job status as "pending", "interview", or "declined".
- **Protected Routes:** Only authenticated users can access and manage their jobs.
- **Responsive UI:** Built with React, React Router, and Bootstrap for a modern user experience.

## Tech Stack

- **Frontend:** React, React Router, Bootstrap, Axios, Vite
- **Backend:** Node.js, Express, Mongoose, MongoDB, JWT, bcryptjs
- **Other:** dotenv, CORS, express-async-errors

## Project Structure

```
job-manager/
│
├── frontend/   # React app (Vite)
│   └── src/
│       ├── pages/         # Main pages (Login, Signup, Dashboard, etc.)
│       ├── components/    # Reusable UI components
│       └── router.jsx     # App routes
│
└── backend/    # Node.js/Express API
    ├── controllers/   # Route logic for jobs and auth
    ├── models/        # Mongoose models (User, Job)
    ├── routes/        # API endpoints
    ├── middlewares/   # Error handling, authentication
    └── db/            # Database connection
```

