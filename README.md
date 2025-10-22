# Seti

A Prediction Markets for Sports.

[![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)]()
[![Chain](https://img.shields.io/badge/Base-Black?style=for-the-badge&logo=ethereum&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)]()

> **A lean, user-first prediction market for sports fans — built on Base.**

Seti is a **miniapp** that brings **real-world forecasting** to the masses through **simple UX, stablecoin betting, and on-chain resolution**. Originally born at the **Nairobi MiniHack**, Seti has evolved from its Sui roots into a focused **Base-native application** designed for **mainstream adoption**.

No noise. No complexity. Just clear markets on **Sports match outcomes**.

All bets use **stablecoins**, resolve via **Chainlink oracles**, and onboard users seamlessly through **account abstraction**.

🔗 **Live Demo**: [TBA]

---

## ✨ Why Seti?

- **Curated markets only**: Fewer choices = faster decisions = better for new users  
- **Gasless onboarding**: Email-style sign-in via **ERC-4337 smart contract wallets**  
- **Real-time resolution**: Outcomes verified by **Chainlink Functions**  
- **Built on Base**: Low-cost, high-engagement UX on Base  

---

## 🛠️ Tech Stack

| Layer          | Technologies                                      |
|----------------|---------------------------------------------------|
| **Frontend**   | Next.js, TypeScript, Tailwind CSS                 |
| **Starter**    | [`create onchain`](https://onchainkit.xyz/)       |
| **Wallet**     | RainbowKit + Viem + Wagmi                         |
| **AA**         | ERC-4337 (via Alchemy)          |
| **Blockchain** | Solidity (Base), Chainlink Oracles                |
| **Backend**    | Flask (for auxiliary services, if needed)         |

---

## 🚀 Core Features

- **Marketplace**: Browse live prediction markets by category  
- **Stablecoin Betting**: Trade with USDC or equivalent  
- **Market Creation**: Artists, analysts, or admins can propose markets (hybrid curation model)  
- **Oracle Resolution**: Final outcomes fetched via **Chainlink Functions**  
- **Portfolio**: Track open positions, claim winnings, view history  

---

## 🏗️ Quick Start

### Prerequisites
- Node.js 18+
- A Base-compatible wallet (e.g., Coinbase Wallet, MetaMask)
- [WalletConnect Project ID](https://cloud.walletconnect.com/)

### Installation
```bash
cd src

# Install dependencies
npm i

# Start a local development server
npm run dev

# Set up environment
cp .env.example .env.local
```