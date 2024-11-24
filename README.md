# Booking App

A full-stack booking application built with Node.js, Express.js, and React.js, designed to handle booking processes efficiently. The backend API is developed in Node.js, while the frontend is powered by React and styled using Tailwind CSS.

## Folder Structure

### **Project Root**
- **api/**: Contains backend-related code for managing bookings.
- **Client/**: Houses frontend-related code for user interface and interactions.

---

### **Backend (api)**
```
api/
├── models/         # Contains database models (e.g., User, Booking).
├── node_modules/   # Contains Node.js dependencies.
├── uploads/        # Stores uploaded files, such as images/documents.
├── .gitignore      # Specifies files to ignore in version control.
├── .env            # Stores environment variables.
├── index.js        # Entry point for the backend server.
├── package.json    # Backend dependencies and scripts.
├── yarn.lock       # Locks dependencies for consistent installs.
```

#### **Key Backend Highlights**
- Built with **Node.js** and **Express.js**.
- **MongoDB** as the database for storing user and booking data.
- **Multer** for handling file uploads in the `uploads/` directory.
- Uses an `.env` file for managing sensitive environment variables.

---

### **Frontend (Client)**
```
Client/
├── node_modules/   # Contains React.js dependencies.
├── public/         # Static files like images and icons.
├── src/            # Main source directory for React components and logic.
├── .gitignore      # Specifies files to ignore in version control.
├── eslint.config.js # Configures linting rules.
├── index.html      # Main HTML template.
├── package.json    # Frontend dependencies and scripts.
├── postcss.config.js # PostCSS configuration for Tailwind CSS.
├── README.md       # Frontend-specific documentation.
├── tailwind.config.js # Configuration for Tailwind CSS.
├── vite.config.js  # Configuration for the Vite build tool.
├── yarn.lock       # Locks dependencies for consistent installs.
```

#### **Key Frontend Highlights**
- Built with **React.js** and styled using **Tailwind CSS**.
- **Vite** for blazing-fast builds and development.
- Modular and component-based architecture.
- **ESLint** for code linting and maintaining code quality.

---

## How to Run the Project

### **Backend Setup**
1. Navigate to the `api` directory:
   ```bash
   cd api
   ```
2. Install backend dependencies:
   ```bash
   yarn install
   ```
3. Create a `.env` file in the `api` directory with necessary environment variables:
   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
4. Start the backend server:
   ```bash
   yarn start
   ```

### **Frontend Setup**
1. Navigate to the `Client` directory:
   ```bash
   cd Client
   ```
2. Install frontend dependencies:
   ```bash
   yarn install
   ```
3. Start the development server:
   ```bash
   yarn dev
   ```

---

## Technologies Used

### Backend
- **Node.js**
- **Express.js**
- **MongoDB**
- **Multer**

### Frontend
- **React.js**
- **Vite**
- **Tailwind CSS**

---

## Features
1. User Authentication: Sign up, login, and secure sessions.
2. Booking Management: Create, view, update, and cancel bookings.
3. File Uploads: Handle file uploads for booking details or profiles.
4. Responsive Design: Mobile-friendly interface.

---

## Contributing

Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
