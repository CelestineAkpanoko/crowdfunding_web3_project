# Crowdfunding Web3 Project

This is a decentralized crowdfunding platform built with Web3 technologies. The project includes both the frontend and smart contracts that enable users to contribute to various crowdfunding campaigns on the blockchain.

## Project Structure

- **client/**: Contains the frontend code, built using modern web technologies. It includes:
  - `index.html`: The main entry point of the web app.
  - `src/`: The source code directory for the client-side application, including React components and assets.
  - `package.json` and `package-lock.json`: Dependency management for the client-side project.
  - `tailwind.config.js`, `postcss.config.js`: Configuration for styling the web app using Tailwind CSS.
  - `vite.config.js`: Configuration for Vite, a fast build tool for modern web development.
  
- **web3/**: Contains the backend for the smart contract and blockchain interactions.
  - **contracts/**: Directory containing the Solidity smart contracts for crowdfunding functionality.
  - `hardhat.config.js`: Configuration for the Hardhat development environment, which is used for compiling and deploying smart contracts.
  - `package.json` and `yarn.lock`: Dependency management for the Web3 backend.
  
## Features

- Users can create and fund crowdfunding campaigns.
- Campaigns are powered by smart contracts, ensuring transparency and security.
- The frontend is built to be interactive and easy to use with Web3 integration.

## Getting Started

### Prerequisites

- Node.js
- Yarn or npm
- Hardhat for smart contract deployment

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/CelestineAkpanoko/crowdfunding_web3_project.git
