# Decentralized Voting App

This repository contains the code for a decentralized voting application built using Solidity smart contracts and React.js for the frontend. The backend and frontend are connected using web3.js, and Ganache is used to fetch the account addresses.

## Features

- Secure and transparent voting process using blockchain technology.
- Decentralized architecture ensures immutability and tamper-proof results.
- User-friendly interface built with React.js.
- Integration with Ganache for testing and development purposes.

## Prerequisites

Before running the application, make sure you have the following dependencies installed:

- Node.js: [https://nodejs.org](https://nodejs.org)
- Ganache: [https://www.trufflesuite.com/ganache](https://www.trufflesuite.com/ganache)

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/decentralized-voting-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd decentralized-voting-app
   ```

3. Install the required packages for both backend and frontend:

   ```bash
   cd backend
   npm install

   cd ../frontend
   npm install
   ```

4. Update the `truffle-config.js` file in the `backend` directory to configure the network settings according to your environment, such as the network provider URL and port.

## Usage

1. Start Ganache to create a local blockchain network.

2. Deploy the smart contracts to the local network using Truffle:

   ```bash
   cd backend
   npx truffle migrate
   ```

3. Start the backend server:

   ```bash
   cd backend
   npm start
   ```

4. Start the frontend development server:

   ```bash
   cd frontend
   npm start
   ```

5. Open your web browser and visit [http://localhost:3000](http://localhost:3000) to access the decentralized voting application.





## Acknowledgments

- This project is inspired by the idea of decentralized voting systems.
- Special thanks to the developers and contributors of Solidity, React.js, web3.js, and Ganache for their excellent tools and libraries.
