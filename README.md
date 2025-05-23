# EmployWiseAssignment

EmployWiseAssignment is a React + TypeScript application that provides a user management system. It allows users to log in, view a list of users, edit user details, and delete users. The application is styled using Tailwind CSS and communicates with the [Reqres API](https://reqres.in) for data.

## Features

- **Authentication**: Login functionality with token-based authentication.
- **User Management**:
  - View a paginated list of users.
  - Search users by name or email.
  - Edit user details.
  - Delete users.
- **Protected Routes**: Ensures only authenticated users can access certain pages.
- **Responsive Design**: Fully responsive UI built with Tailwind CSS.

## Tech Stack

- **Frontend**: React, TypeScript, React Router, Tailwind CSS
- **State Management**: React's `useState` and `useEffect` hooks
- **API Communication**: Axios
- **Utilities**: React Hot Toast for notifications
- **Build Tool**: Vite

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd employwise-assignment

npm install

npm run dev

Open the application in your browser at http://localhost:5173.

Deployment
The application is deployed and accessible at: https://employwisassignment.netlify.app/ ```