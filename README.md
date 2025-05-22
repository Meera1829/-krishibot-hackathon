# -krishibot-hackathon
AI-powered Ethereum agent for farmers to sell crops &amp; claim subsidies
 🌾 KrishiBot – AI Agent for Market Access & Subsidy Claims

      🚀 Built for Agentic Ethereum Hackathon India 2025

---

🧠 Project Overview

KrishiBot is an AI-powered decentralized application (dApp) that empowers Indian farmers by:

- Predicting fair prices for their produce using a user-friendly frontend.
- Enabling automatic subsidy application and verification using Ethereum smart contracts.
- Simulating integration with Bharat Stack (Aadhaar API and UPI).

It bridges AI, Web3, and public infrastructure to solve real challenges in agri-market access and financial inclusion.

---

 ✅ Features

- 🌾 Crop price prediction and visualization
- 🪙 Subsidy eligibility verification via Ethereum smart contracts
- 🔐 Aadhaar-based identity input simulation
- 📲 Simulated UPI disbursal flow
- 📊 Clean and interactive frontend dashboard

---
🛠 Tech Stack

| Layer         | Tools Used                         |
|---------------|------------------------------------|
| Frontend      | HTML, CSS, JavaScript              |
| Smart Contract| Solidity, Remix IDE (EVM-based)    |
| Identity APIs | Aadhaar (Simulated)                |
| Payments      | UPI Integration (Simulated)        |
| Blockchain    | Ethereum testnet (for demo)        |

---

⚙️ Setup Instructions

 Frontend (Local Setup)
1. Unzip the KrishiBot-Frontend.zip folder.
2. Double-click `index.html` to open the app in a browser.
3. Use the form to simulate crop price predictions and subsidy display.

 Backend (Smart Contract in Remix)
1. Go to [Remix IDE](https://remix.ethereum.org)
2. Create a new file: `KrishiBot.sol`
3. Paste the smart contract code from KrishiBot-Backend
4. Compile and deploy the contract on the JavaScript VM (or testnet)
5. Use the registerFarmer and claimSubsidy functions to simulate operations

---

🧪 How to Use the Smart Contract

- `registerFarmer(name, aadhaar, cropId, quantity)` → stores farmer data
- `claimSubsidy()` → checks eligibility and marks subsidy as claimed
- `getFarmer(address)` → fetches all stored data for a farmer
- `isEligible(address)` → returns true/false if the user qualifies

🔒 Note: Subsidy claim logic is simulated for hackathon purposes.

---
 👨‍👩‍👧 Team Members

| Name             | Role             |
|------------------|------------------|
| Meera Sri KA     | Developer        |
| Maheshkumar K    | Developer        |
| Kanishkar        | Developer        |
| Kamalesh         | Developer        |








