# Food-Ordering-App---Assignment
Alfred

This is a food ordering web application built with React.js for the frontend and Node.js with Express for the backend. The app allows users to browse restaurants, view their menus, and place orders. Orders and tracking information are stored and managed in JSON files on the backend.

## Features

- View a list of restaurants
- View menu items for a selected restaurant
- Confirm and place orders
- Track orders
- Responsive design with interactive effects

## Technologies Used

- Frontend: React.js, Axios, Tailwind CSS
- Backend: Node.js, Express.js
- Data Storage: JSON files

## Setup and Running the Project

### Prerequisites

- Node.js and npm installed
- Git installed

### Installation

1. **Clone the repository:**

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install backend dependencies:**

    ```bash
    cd backend
    npm install
    ```

3. **Install frontend dependencies:**

    ```bash
    cd ../frontend
    npm install
    ```

### Running the Project

1. **Start the backend server:**

    ```bash
    cd backend
    npm start
    ```

    The backend server will start on `http://localhost:5000`.

2. **Start the frontend development server:**

    ```bash
    cd ../frontend
    npm start
    ```

    The frontend development server will start on `http://localhost:3000`.

### Project Structure

- `backend/`: Contains the backend server code
- `backend/data/`: JSON files for storing restaurants, menus, orders, and tracking information
- `frontend/`: Contains the React frontend code
- `frontend/src/components/`: React components for the application
- `frontend/src/pages/`: React pages for different routes in the application

### API Endpoints

- **GET /api/restaurants**: Fetch all restaurants
- **GET /api/restaurants/:id**: Fetch restaurant by ID
- **GET /api/menu/:restaurantId**: Fetch menu items by restaurant ID
- **GET /api/menu/item/:id**: Fetch menu item by ID
- **POST /api/orders**: Add a new order
- **POST /api/tracking**: Add tracking information for an order

### Git Commands to Push Code to Repository

1. **Initialize a new git repository (if not already initialized):**

    ```bash
    git init
    ```

2. **Add all files to the repository:**

    ```bash
    git add .
    ```

3. **Commit the changes:**

    ```bash
    git commit -m "Initial commit"
    ```

4. **Add the remote repository URL:**

    ```bash
    git remote add origin <repository-url>
    ```

5. **Push the code to the repository:**

    ```bash
    git push -u origin main
    ```

### Usage

- Visit `http://localhost:3000` to view the application
- Click on a restaurant to view its menu
- Click on a menu item to confirm an order
- Visit the Orders page to see the list of orders
- Visit the Tracking page to see the tracking details of orders

### License

This project is licensed under the MIT License.
