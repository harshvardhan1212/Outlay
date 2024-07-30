## Otlay: Empower Your Finance

### Overview

Otlay is a comprehensive financial management application designed to help users better manage their finances. Built using the MERN stack (MongoDB, Express.js, React, Node.js), Otlay offers features such as budgeting, expense tracking, and financial insights.

### Features

- **User Authentication:** Secure login and registration using JWT (JSON Web Tokens).
- **Expense Tracking:** Add, view, and categorize expenses.
- **Budget Management:** Set and track budgets for different categories.
- **Financial Insights:** Visualize your spending habits with charts and analytics.
- **Responsive Design:** Optimized for both desktop and mobile devices.

### Tech Stack

- **Frontend:** React, Redux, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT

### Getting Started

To get a local copy of the project up and running, follow these steps:

#### Prerequisites

- Node.js (version 14.x or higher)
- npm (version 6.x or higher)
- MongoDB (local or cloud-based)

#### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/otlay.git
   cd otlay
   ```

2. **Install Dependencies:**

   Navigate to the client and server directories and install the necessary packages.

   ```bash
   # For the server
   cd server
   npm install

   # For the client
   cd ../client
   npm install
   ```

3. **Set Up Environment Variables:**

   Create a `.env` file in the server directory and add the following content:

   ```plaintext
   DBURL=mongodb://your_mongodb_url
   PORT=your_localhost_port
   JWT_SEC=your_jwt_secret_key
   MAILER = "
   EMAILPASS = ""
   OTPSEC = "THIS IS SECRET KEY FOR OTP"
   ```

   Replace `your_mongodb_url`, `your_localhost_port`, and `your_jwt_secret_key` with your actual MongoDB URL, desired port number, and a secure secret key for JWT tokens.

4. **Run the Application:**

   Start both the server and client.

   ```bash
   # Start the server
   cd server
   npm start

   # Start the client
   cd ../client
   npm start
   ```

   The application should now be running on `http://localhost:3000` for the client and `http://localhost:your_port` for the server.

### Contribution

Contributions are welcome! Please fork the repository and submit a pull request.

### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

### Contact

For any questions or suggestions, feel free to contact me at [your-email@example.com](mailto:your-email@example.com).

---

Feel free to customize this template according to your project's specific details and requirements.

![image](https://github.com/user-attachments/assets/8d647101-4e77-405d-b9f4-8a25baa0e589)
![image](https://github.com/user-attachments/assets/ea9fe62a-6576-4d38-b19b-78cd160ab061)
![image](https://github.com/user-attachments/assets/15f0d32f-22ba-4430-af90-9be61aaa6cbc)


