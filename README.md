
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
- [License](#license)

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

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.



   


![Screenshot from 2021-11-01 18-05-31](https://user-images.githubusercontent.com/91063960/139678469-c631005a-9c20-4321-8022-24f4573427b7.png)
![Screenshot from 2021-11-01 18-05-52](https://user-images.githubusercontent.com/91063960/139678483-ca95e74e-44a5-422c-9cac-4bfe463215ef.png)
![Screenshot from 2021-11-01 18-06-08](https://user-images.githubusercontent.com/91063960/139678489-03130e57-7e0b-4bb0-96f6-f4ec85b8efbe.png)
![Screenshot from 2021-11-01 18-06-32](https://user-images.githubusercontent.com/91063960/139678548-e58c550e-51c5-4695-a0c3-d6563737548a.png)
![Screenshot from 2021-11-01 18-07-35](https://user-images.githubusercontent.com/91063960/139678663-177aedd5-e622-4441-871b-e0af7be1e363.png)
![Screenshot from 2021-11-01 18-08-34](https://user-images.githubusercontent.com/91063960/139678729-432bb265-9d98-4a2d-8c27-d66eb2f09b26.png)
![Screenshot from 2021-11-01 18-08-40](https://user-images.githubusercontent.com/91063960/139678735-0ac4e3e8-591d-4652-8965-22c830fa94db.png)
![Screenshot from 2021-11-01 18-09-33](https://user-images.githubusercontent.com/91063960/139678737-8d069f75-9d7f-44ff-8e37-4be34ebc95cd.png)

---

Thank you for checking out the Flipkart Clone project. If you have any questions or feedback, please feel free to open an issue or reach out to the maintainers. Happy coding!



  
## Installation

  1. Clone/Download the repo.
  2. Run npm install on client as well as server.
  3. Run npm start both server and  client  to spin the up the local dev server port 8000,3000,(http://localhost:8000),(http://localhost:3000).
