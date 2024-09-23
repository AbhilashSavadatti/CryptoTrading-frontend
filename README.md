# Crypto Trading Platform

Welcome to the **Crypto Trading Platform** GitHub repository! This platform is designed to offer seamless crypto trading, portfolio management, wallet services, and enhanced security features for users. Built with modern technologies, the platform leverages APIs and efficient backend services to create a smooth and secure trading experience.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
  - [AI Chat Bot](#ai-chat-bot)
  - [Trading Capabilities](#trading-capabilities)
  - [Portfolio Management](#portfolio-management)
  - [Wallet Services](#wallet-services)
  - [Authentication and Security](#authentication-and-security)
- [Technology Stack](#technology-stack)
  - [Backend Development](#backend-development)
  - [Frontend Development](#frontend-development)
  - [APIs](#apis)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [License](#license)

---

## Overview

This **Crypto Trading Platform** is a robust web application that allows users to trade cryptocurrencies, manage their portfolios, transfer funds between wallets, and secure their accounts with advanced authentication methods. The platform is designed with high scalability and security in mind, ensuring a smooth and safe experience for crypto traders.

---

## Features

### 1. AI Chat Bot
- **Functionality**: Answers crypto-related queries such as real-time prices, market cap, and other data.
- **APIs**: Integrates with [Gemini API](https://docs.gemini.com/rest-api) and [CoinGecko API](https://www.coingecko.com/en/api) to fetch the latest data.
- **Technology**: Implements Natural Language Processing (NLP) to understand user queries and provide accurate responses.

### 2. Trading Capabilities
- **Buy & Sell Crypto**: Users can trade cryptocurrencies directly on the platform.
- **APIs Used**: Leverages the Gemini API for seamless trade execution.

### 3. Portfolio Management
- **Overview**: View and manage crypto holdings, track portfolio performance, and analyze investments.
- **Technology**: The portfolio data is fetched from backend services, offering real-time tracking and analysis.

### 4. Wallet Services
- **Wallet-to-Wallet Transfers**: Facilitates secure transfers between user wallets.
- **Withdrawal to Bank Account**: Converts cryptocurrency to fiat currency and withdraws funds to the user’s bank account.
- **Add Balance to Wallet**: Allows users to fund their wallets to perform trading activities.

### 5. Authentication and Security
- **User Login & Registration**: Secure authentication powered by Spring Security.
- **Two-Factor Authentication (2FA)**: Adds an extra layer of security.
- **Forgot Password**: Allows users to recover their accounts securely via email and OTP verification.

---

## Technology Stack

### Backend Development
- **Spring Boot**: Provides a powerful backend framework to develop REST APIs and services.
- **MySQL**: A reliable relational database for storing user data, transaction history, and other important records.
- **Spring Security**: Implements secure user authentication and authorization with added 2FA support.

### Frontend Development
- **React**: The frontend is built with React to provide a dynamic and responsive user interface.
- **Tailwind CSS**: Utility-first CSS framework for efficient design and styling of the application.
- **Redux**: Manages the global state of the application, ensuring predictable behavior across components.

### APIs
- **Gemini API**: Enables real-time trading and wallet functionalities.
- **CoinGecko API**: Provides up-to-date cryptocurrency data, including market prices and market cap.

---

## Project Structure

```bash
crypto-trading-platform/
│
├── backend/              # Spring Boot application with APIs and services
│   ├── src/              # Java source code
│   └── resources/        # Application properties and configurations
│
├── frontend/             # React application for the UI
│   ├── src/              # React components and views
│   ├── public/           # Static files
│   └── styles/           # Tailwind CSS configurations
│
├── database/             # MySQL scripts and migrations
│
├── docs/                 # Documentation and guides
│
└── README.md             # Project overview and instructions


## Installation

### Backend (Spring Boot)
1. Clone the repository and navigate to the `backend` directory:
   ```bash
   git clone https://github.com/yourusername/crypto-trading-platform.git
   cd crypto-trading-platform/backend
   ```
2. Install dependencies:
   ```bash
   ./mvnw clean install
   ```
3. Configure the `application.properties` file to connect to your MySQL database and API keys:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/crypto_db
   spring.datasource.username=your_mysql_user
   spring.datasource.password=your_mysql_password

   gemini.api.key=your_gemini_api_key
   coingecko.api.key=your_coingecko_api_key
   ```
4. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

### Frontend (React)
1. Navigate to the `frontend` directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the application:
   ```bash
   npm start
   ```

---

## Usage

1. **Register/Login**: Create an account and securely log in to access trading and portfolio features.
2. **Trading**: Buy and sell cryptocurrencies using the Gemini API.
3. **Portfolio Management**: View real-time data on your holdings and track performance.
4. **Wallet Services**: Transfer between wallets, withdraw to bank accounts, and add funds.

---

## Contribution

We welcome contributions to enhance the platform! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push the branch (`git push origin feature-name`).
5. Create a Pull Request on GitHub.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to reach out if you have any questions or issues!

