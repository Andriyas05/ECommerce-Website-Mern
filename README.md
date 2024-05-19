
# Flipkart Clone - MERN Stack Project

## Introduction

Welcome to the Flipkart Clone project! This project is a comprehensive e-commerce application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). It replicates many of the core features of Flipkart, including user authentication, product browsing, shopping cart functionality, and order management. Additionally, it integrates the Paytm payment gateway for processing transactions.

## Demo video
[![Watch the video](https://img.youtube.com/vi/B-1uk1vw5N4/maxresdefault.jpg)](https://youtu.be/B-1uk1vw5N4)


## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Contributing](#contributing)


## Features

- User authentication (Sign up, Log in, Log out)
- Product listing and details
- Search and filter functionality
- Shopping cart management
- Paytm payment gateway integration
- Responsive design

## Technologies Used

- **Frontend:**
  - React.js
  - Redux for state management
  - Bootstrap for styling

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB

- **Payment Gateway:**
  - Paytm

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Andriyas05/Ecommerce-Website-Mern.git
   cd Ecommerce-Website-Mern
   ```

2. **Install dependencies for both frontend and backend:**
   ```bash
   # For backend
   cd server
   npm install

   # For frontend
   cd ../client
   npm install
   ```

## Configuration

### Backend Configuration

1. Create a `.env` file in the `backend` directory and add the following environment variables:
   ```plaintext
   PORT=5000
   MONGODB_URL=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret_key>
   PAYTM_MID=<your_paytm_merchant_id>
   PAYTM_KEY=<your_paytm_merchant_key>
   PAYTM_WEBSITE=<your_paytm_website>
   PAYTM_CHANNEL_ID=<your_paytm_channel_id>
   PAYTM_INDUSTRY_TYPE=<your_paytm_industry_type>
   ```

### Frontend Configuration

1. Create a `.env` file in the `frontend` directory and add the following environment variables:
   ```plaintext
   REACT_APP_API_URL=http://localhost:5000/api
   ```

## Running the Application

1. **Start the backend server:**
   ```bash
   cd server
   npm start
   ```

2. **Start the frontend development server:**
   ```bash
   cd client
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` to view the application.

## Project Structure

```plaintext
Ecommerce-Website-Mern/
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── config/
│   ├── .env
│   └── server.js
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── App.js
│   │   ├── index.js
│   └── .env
│
└── README.md
```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes.
4. Submit a pull request with a detailed description of your changes.


## Photos





![Screenshot (1351)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/e23f4182-1d25-408f-8f23-8915e8d79b6f)
![Screenshot (1352)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/e21cf28f-7ea9-42ad-b842-0a1229e05226)
![Screenshot (1353)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/f1f502bd-1d3a-4ac2-95a0-7cbcbb4ed237)
  ![Screenshot (1354)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/2197ee1d-414c-47e0-84a3-584c440545d8)
![Screenshot (1355)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/b40b3d9f-cafb-4005-b8d5-6706dc8b1aae)
![Screenshot (1356)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/09ce16bd-aae0-4016-81f5-35b9ddc9fba6)
![Screenshot (1357)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/8f9022f0-b007-4a90-8b72-672d6fa20495)
![Screenshot (1359)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/d97f51ce-ae48-4961-a22d-d450bb335ecc)
![Screenshot (1360)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/387597f4-60a6-4973-a2b9-c83dc06ea737)
![Screenshot (1358)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/940b69e3-ed97-4c64-b30c-da5a57d7790a)
![Screenshot (1364)](https://github.com/Andriyas05/ECommerce-Website-Mern/assets/99260104/4017ac62-0170-4385-a585-fb138a8488b1)

---

Thank you for checking out the Flipkart Clone project. If you have any questions or feedback, please feel free to open an issue or reach out to the maintainers. Happy coding!



  
## Installation

  1. Clone/Download the repo.
  2. Run npm install on client as well as server.
  3. Run npm start both server and  client  to spin the up the local dev server port 8000,3000,(http://localhost:8000),(http://localhost:3000).
