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

