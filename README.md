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
