# Debinum Faucet

## Overview
The Debinum Faucet is a React-based web application designed to interact with a series of smart contracts on Ethereum networks. This project aims to create a system for distributing test tokens, simulating token transactions and interactions within Ethereum networks.

### Project Details
- **Name:** debinum-faucet
- **Version:** 0.0.1
- **Author:** ebinum83
- **Description:** A Faucet that drips Test Tokens on Ethereum networks.
- **Dependencies:** React, Bootstrap, React Bootstrap, Ethers, Web3, and others.

## React Frontend Application
The frontend is built using React and styled with React Bootstrap. It provides a user interface for interacting with the smart contracts.

### Key Functionalities:
- Token distribution interface.
- Network selection and interaction.
- Responsive design for various devices.

### Running the Application
- **Development Server:** Run `npm start` to start the app in development mode.
- **Building:** Use `npm run build` to build the app for production.

## Smart Contracts
The project includes several smart contracts written in Solidity, such as `Aave.sol`, `CakeToken.sol`, `DeboToken.sol`, and more.

### Contracts Overview:
- **Aave, CakeToken, DeboToken, etc.:** These contracts simulate various ERC-20 tokens.
- **Faucet:** The main contract that manages the distribution of test tokens.

### Contract Deployment
The contracts can be compiled and deployed using Truffle.

## Deploying with Truffle
To deploy these contracts using Truffle:
1. **Compile Contracts:** Run `yarn compile` to compile the contracts.
2. **Deploy:** Use `truffle deploy --network <network_name>` to deploy to the specified network.
3. **Network Configuration:** Configurations for different networks can be found in `truffle-config.js`.

## License
This project is licensed under the MIT License.

# debinum-faucet
https://debinum.github.io/debinum-faucet
