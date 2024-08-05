# Madclub-Decentralized-Credit-Scoring-System
🌟 Decentralized Credit Scoring System 🌟
Welcome to the Decentralized Credit Scoring System project! This innovative solution leverages blockchain technology to provide a transparent, secure, and immutable credit scoring mechanism. Our system integrates various data sources through APIs to gather and validate comprehensive financial and non-financial data, ensuring accurate credit assessments.

🚀 Project Overview
The Decentralized Credit Scoring System offers a user-friendly interface with real-time updates, providing users with insights into their credit scores and financial health. By addressing the limitations of traditional credit scoring models, our system offers a decentralized, transparent, and efficient solution.

📝 Features

🔒 Data Security & Privacy: Blockchain technology ensures data is secure and immutable.

🌐 Comprehensive Data Integration: APIs gather and validate data from multiple sources.

📊 Accurate Credit Assessments: Holistic view of creditworthiness using financial and non-financial data.

💡 Real-Time Updates: Users receive instant insights into their credit scores.

🔗 Transparent & Decentralized: Eliminates the need for centralized credit bureaus.

📈 Future Plans


## Expand Data Sources: Integrate more data points to enhance credit assessment accuracy.
AI Integration: Implement AI algorithms to provide predictive analytics and personalized financial advice.
Global Expansion: Adapt the system to various countries and regions for broader adoption.
User Education: Develop educational resources to help users understand and improve their credit scores.

## 🛠️ Technology Stack
Backend: Python, Flask
Frontend: JavaScript, React
Blockchain: Solidity, Ethereum
Database: PostgreSQL
APIs: Various financial and non-financial data sources

## ⚙️ Installation & Setup
Prerequisites
Python 3.8+
Node.js
PostgreSQL
Truffle
Ganache
Steps
Clone the repository:

# Decentralized Credit Scoring System

## Introduction
This project is a decentralized credit scoring system built using Flask for the backend, React for the frontend, and Solidity for the smart contracts. The project integrates external APIs to gather financial and non-financial data to calculate credit scores stored on the blockchain for transparency and security.

## Technology Stack
- **Frontend**: React
- **Backend**: Flask
- **Blockchain**: Solidity, Web3, Truffle
- **Database**: SQLite (for initial prototyping)

## Features
- User registration and login
- Credit score calculation
- Integration with external APIs
- Decentralized data storage on the blockchain

## Setup Instructions

## Prerequisites
- [Node.js](https://nodejs.org/) and npm
- [Python](https://www.python.org/)
- [Truffle](https://www.trufflesuite.com/truffle)
- [Ganache](https://www.trufflesuite.com/ganache)

## 1. Clone the Repository

git clone <repository-url>
cd decentralized-credit-scoring-system

git clone https://github.com/yourusername/decentralized-credit-scoring.git
cd decentralized-credit-scoring
Install backend dependencies:


cd backend
pip install -r requirements.txt
Install frontend dependencies:


cd frontend
npm install
Setup PostgreSQL:

Create a database named credit_scoring.
Update the database configuration in backend/config.py.
Run migrations:

cd backend
flask db upgrade
Start the backend server:

flask run
Start the frontend server:

cd frontend
npm start
Deploy Smart Contracts:

Start Ganache
Deploy contracts using Truffle

truffle migrate --reset
Set Up the Blockchain Environment
Install Truffle and Ganache:

npm install -g truffle
Run Ganache:
Start Ganache GUI or run it from the command line:

ganache-cli
Compile and Deploy Smart Contracts:
Navigate to the contracts directory:

cd ../contracts
Initialize Truffle Project:

truffle init
Create a Simple Smart Contract (CreditScore.sol):
solidity

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract CreditScore {
    mapping(address => uint) public creditScores;

    function setCreditScore(address user, uint score) public {
        creditScores[user] = score;
    }

    function getCreditScore(address user) public view returns (uint) {
        return creditScores[user];
    }
}
Compile Contracts:

truffle compile
Deploy Contracts:
truffle migrate

📂 Project Structure

backend/: Contains the Flask backend code.

frontend/: Contains the React frontend code.

contracts/: Contains the Solidity smart contracts.

migrations/: Database migration files.

tests/: Test cases for the backend and contracts.

## USE THIS FILE FOR TESTING 

credit_data.csv

🌍 Contributing
We welcome contributions from the community! Please fork the repository and submit pull requests.

📝 License
This project is licensed under the MIT License.

📞 Contact
If you have any questions or feedback, please reach out to us at tharak.nagaveti@gmail.com


