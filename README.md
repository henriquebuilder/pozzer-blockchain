# Pozzer — DePIN Protocol for Decentralized Infrastructure

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6)
![React](https://img.shields.io/badge/React-19-61DAFB)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers-F38020)
![Web3](https://img.shields.io/badge/Web3-Multi--chain-purple)
![Solidity](https://img.shields.io/badge/Solidity-Smart%20Contracts-363636)

Full-stack Web3 protocol designed for decentralized infrastructure participation, combining wallet-based authentication, multi-chain interaction, gamification, and edge-native architecture.

> Built as a scalable **testnet environment** to validate real-world DePIN mechanics and user participation.

---

## 🚀 Project Summary

Pozzer is a DePIN (Decentralized Physical Infrastructure Network) protocol designed to enable users to participate in decentralized infrastructure through verifiable actions, network validation, and reward distribution.

The platform combines:

- Web3 wallet authentication (signature-based)
- Edge-native backend (Cloudflare Workers)
- Multi-chain infrastructure (EVM-compatible networks)
- Gamified participation and reward system

This repository represents a **testnet-phase implementation of a scalable Web3 protocol**, focused on performance, security, and real-world architecture patterns.

---

## 🌟 Overview

Pozzer enables users to interact with decentralized infrastructure through:

- Wallet-based authentication
- Mission-based participation
- Validator/network simulation
- Reward distribution systems

The system is built using an **edge-first architecture**, delivering:

- Low-latency API responses
- Scalable backend execution
- Secure multi-chain interactions

---

## 🧠 Key Engineering Highlights

- 20+ REST API endpoints (edge-native)
- 13 relational database tables (Cloudflare D1)
- Wallet authentication using nonce + signature verification
- Multi-chain integration (Ethereum, Polygon, BSC, Arbitrum)
- Real-time network monitoring and validator simulation
- Security layers: rate limiting, logging, input validation

---

## 🔄 User Flow

1. **Wallet Connection**
   - User connects via Web3Modal / WalletConnect

2. **Authentication**
   - Signature verification using nonce-based flow

3. **Participation**
   - User completes missions and interacts with the system

4. **Validation**
   - Backend processes and validates actions

5. **Rewards**
   - Progression and rewards updated dynamically

---

## 🛠️ Core Components

### 🔐 Web3 Authentication
- Nonce generation and validation
- Signature verification (EVM wallets)

### ⚙️ API Layer
- Cloudflare Workers (serverless edge runtime)
- Hono framework (lightweight API routing)

### 🌐 Multi-chain Layer
- Ethereum
- Polygon
- BSC
- Arbitrum

### 🎮 Gamification Engine
- Mission system
- XP and reward distribution
- Progression tiers

### 🧩 Admin System
- Verification queue
- Moderation tools
- Security monitoring

---

## 🏗️ Architecture

**Frontend**
- React
- TypeScript
- Tailwind CSS
- React Router

**Backend**
- Cloudflare Workers (edge functions)
- Hono

**Database**
- Cloudflare D1 (SQLite serverless)

**Storage**
- Cloudflare R2

**Web3 Layer**
- Ethers.js
- Web3Modal
- WalletConnect

---

## ⚡ Technical Challenges Solved

- Secure wallet authentication without exposing private keys
- Low-latency execution in serverless environments
- Anti-abuse mechanisms for reward systems (anti-sybil logic)
- Multi-chain compatibility in a unified interface
- Scalable validation and participation modeling

---

## 🔐 Security

- Wallet signature verification (nonce-based)
- JWT authentication for admin
- bcrypt password hashing
- Rate limiting (IP + wallet)
- Request logging and anomaly detection
- Input sanitization and strict endpoint validation

---

## 📊 Project Highlights

- 20+ API endpoints
- 13 database tables
- Multi-chain wallet support
- Edge deployment (Cloudflare)
- Real-time system design

---

## 🚀 Live Demo

Testnet environment is live:

🔗 https://www.pozzer.io/

Features:
- Wallet connection
- Mission participation
- Real-time backend validation
- Gamified progression

---

## 📂 Documentation

Technical documentation available:
# docs/
-├── ARCHITECTURE.md
-├── SECURITY.md
-├── ROUTES.md


---

## 💻 Run Locally

### Install dependencies
```bash
npm install
```

Setup environment
```bash
cp .env.example .env
```

Run project
```bash
npm run dev
```

## 🌐 Environment Variables

VITE_WALLETCONNECT_PROJECT_ID=your_id_here
ADMIN_JWT_SECRET=your_secret_here
AUTHORIZED_ADMIN_EMAILS=admin@example.com
TESTNET_UNLOCK_DATE=2025-04-01T00:00:00Z

## ⚠️ Disclaimer

Pozzer is currently operating in a testnet environment.

Certain components — including parts of the validation layer and infrastructure logic — are abstracted to ensure usability and controlled experimentation.

This repository focuses on demonstrating protocol architecture, system design, and engineering decisions, rather than exposing full production infrastructure.

## 📈 Tokenomics (Overview)
Tier-based participation model
Reward multipliers
Mission-driven progression
NFT-based reward concepts (future expansion)

## 🌎 Vision

To build scalable decentralized infrastructure where users can contribute resources, validate networks, and earn rewards — bridging Web3 with real-world systems.

## 🤝 Community
Twitter: @pozzer_depin
Telegram: t.me/pozzerpt
Email: contato@pozzer.io

## 📄 License

MIT
