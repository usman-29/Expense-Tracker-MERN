# Expense Tracker App

An expense tracker application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This app allows users to:

- Add multiple income sources and expenses with titles and dates.
- View a dashboard graph displaying income and expense trends.
- Access a complete history of transactions.

---

## Features

- User-friendly interface to manage income and expenses.
- Dashboard with graphical representation of financial data.
- History section for viewing all transactions.
- Data persistence using MongoDB.
- Secure and efficient backend using Node.js and Express.js.
- Interactive and responsive frontend with React.js.

## Tech Stack

**Frontend:**
- React.js

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB

**Other Tools & Libraries:**
- Chart.js for graphs.
- Axios for API requests.

---

## Installation

### Prerequisites
- Node.js installed on your machine.
- MongoDB server running locally or a cloud MongoDB URI.

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/usman-29/Expense-Tracker-MERN.git
    ```

2. Navigate to the project directory:
    ```bash
    cd expense-tracker
    ```

3. Install dependencies for both frontend and backend:
    ```bash
    cd backend
    npm install
    cd ../frontend
    npm install
    ```

4. Create a `.env` file in the `backend` folder with the following variables:
    ```env
    PORT=5000
    MONGO_URI=your-mongodb-uri
    ```

5. Start the backend server:
    ```bash
    cd backend
    npm start
    ```

6. Start the frontend server:
    ```bash
    cd ../frontend
    npm start
    ```

7. Open your browser and navigate to `http://localhost:3000`.

---

## Usage

- Add income and expense entries by providing a title, amount, and date.
- View the dashboard to analyze your financial trends.
- Check the history to track all your transactions.

---

## Screenshots
![Screenshot (7)](https://github.com/user-attachments/assets/4537aaa0-1404-4f27-b8a9-4e5d099c323b)

![Screenshot (5)](https://github.com/user-attachments/assets/b48d6803-ee8f-4c90-8781-44273ecc2c28)
