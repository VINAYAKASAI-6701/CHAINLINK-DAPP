# 📈 Ethereum Price Tracker — Chainlink DApp

A fully decentralized application (dApp) that fetches and stores the **real-time price of Ethereum (ETH)** using the **Chainlink ETH/USD Data Feed**. Built with **Solidity**, deployed to the **Sepolia testnet**, and connected to a **React frontend** via **Ethers.js**.

---

## 🚀 Features

- ✅ Fetch live ETH/USD price from **Chainlink oracles**
- ✅ Store the latest price **on-chain**
- ✅ Interact via a clean **React UI**
- ✅ **MetaMask** integration for secure transactions

---

## 🧱 Architecture Overview

### 🔹 Smart Contract (Solidity)
- Uses Chainlink Data Feeds to fetch the price of ETH
- Stores the price on-chain

### 🔹 Frontend (React + Ethers.js)
- Connects to the deployed smart contract
- Displays the fetched ETH price
- Allows users to trigger on-chain storage

---

## ⚙️ Setup Instructions

### 🔧 Prerequisites

- Node.js
- Rust (required for Foundry)
- MetaMask extension
- Fuji RPC URL (Infura or Alchemy)

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/VINAYAKASAI-6701/CHAINLINK-DAPP.git
cd CHAINLINK-DAPP

2️⃣ Backend: Smart Contracts
cd backend
forge install smartcontractkit/chainlink-brownie-contracts
forge init
📄 Update your .env file:
PRIVATE_KEY=your_private_key
FUJI_RPC_URL=https://sepolia.infura.io/v3/YOUR_INFURA_KEY
forge compile
forge script script/DeployPriceConsumer.s.sol --broadcast

3️⃣ Frontend Setup
cd ../frontend
npm install bootstrap ethers@5.7.2

✏️ Update App.js:

Add the deployed contract address

Add the ABI of the deployed contract

🚀 Start the app:
npm start

🛠️ Tech Stack:
| Layer          | Technology                  |
| -------------- | --------------------------- |
| Blockchain     | Ethereum (Sepolia Testnet)  |
| Oracle         | Chainlink ETH/USD Data Feed |
| Smart Contract | Solidity                    |
| Deployment     | Foundry (Rust-based)        |
| Frontend       | React.js                    |
| Wallet         | MetaMask                    |
| Web3 Library   | Ethers.js v5.7.2            |
| Styling        | Bootstrap                   |


📁 Project Structure:
CHAINLINK-DAPP/
├── backend/
│   ├── src/
│   │   └── PriceConsumerV3.sol
│   ├── script/
│   │   └── DeployPriceConsumer.s.sol
│   ├── .env
│   └── foundry.toml
└── frontend/
    ├── src/
    │   └── App.js
    └── public/

💡 Learnings:
->Deploying smart contracts using Foundry

->Integrating Chainlink price feeds

->Connecting Web3 frontend via Ethers.js

->Handling wallet-based interactions with MetaMask

->Managing transactions on the Sepolia Testnet

🧪 Test Network:
.Network: Sepolia Testnet

.Contract Address: 0xYourDeployedAddress (replace with your actual address)


--->Feel free to fork, improve, or contribute to this Chainlink Ethereum Price Tracker DApp!

You can save this content as a file named `README.md` and push it to your GitHub repo.

Would you like me to add this to your repo directly and commit it for you?






