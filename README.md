## BLRMS – Blockchain-Based Land Registration and Management System

BLRMS (Blockchain-based Land Registration and Management System) is a decentralized web application designed to improve the security, transparency, and efficiency of land registration and ownership transfer. The system leverages blockchain technology to maintain immutable land records, reduce fraud, and eliminate reliance on intermediaries. The project demonstrates how blockchain and smart contracts can be applied to real-world governance and land management use cases.

**How it works:** sellers list a plot with its registry details and a photo, then pay a survey fee priced by acreage. A surveyor reviews the listing and approves it, which publishes it to the marketplace. Buyers browse government and private lands, see the full price breakdown with taxes, and pay by card or by sending ETH through MetaMask.

**Built with:** React · Express · MongoDB (Mongoose) · Web3.js · Solidity smart contracts (Truffle / Ganache)

### Features
- **Accounts:** sign-up with a unique identification number, bcrypt-hashed passwords, JWT-based login
- **Seller listings:** land details (acres, registration and survey number, locality, status) plus a photo upload
- **Survey fee:** calculated automatically from the land's acreage
- **Surveyor portal:** separate sign-up protected by a department security key; search pending listings by survey number and approve or disapprove them
- **Marketplace:** government and non-government lands, a detailed land page and a Google Maps lookup
- **Finance page:** land price plus property, registration and service tax
- **Payments:** card payment, or Net Banking through a MetaMask (Web3) Ethereum transaction, followed by a confirmation and a printable transaction summary

## Demo

https://github.com/Anikarudy/BLRMS/raw/main/docs/BLRMS_Demo.mp4

[▶ Watch the demo video](docs/BLRMS_Demo.mp4) (about 4½ minutes, no audio). It walks through the full flow: sign-up and login, listing land as a seller, paying the survey fee, surveyor approval, browsing the marketplace and buying land with a crypto wallet.


https://github.com/user-attachments/assets/334446e5-9297-4348-8cdd-2f947822893d


> In the demo, the MetaMask wallet and the blockchain responses are simulated. All other screens are the real app running locally against its Express + MongoDB backend.

## Problem Statement & Key Objectives:
Traditional land registration systems are often centralized and opaque, vulnerable to fraud and data tampering, slow due to heavy paperwork and intermediaries and prone to ownership disputes. BLRMS addresses these challenges by using blockchain as a tamper-proof ledger for land records and transactions, ensuring trust and accountability among all stakeholders.
Objectives:
- Eliminate intermediaries between buyers and sellers
- Provide transparent and immutable land ownership records
- Reduce land-related disputes through verifiable data
- Enable secure and efficient ownership transfer using smart contracts


## Getting Started

Node.js (v14 or above recommended)
npm (comes with Node.js)
MongoDB (for local development)

## Installation

Download and Extract
  Download the project zip file and extract it to your desired directory
  
Install Dependencies
  Open a terminal and navigate to the project directory.
  Run the following command to install all dependencies:
  `npm install`

### Running

`npm start`
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
MongoDB application should be open while running ReactJS frontend.

### Running Backend

`node server.js`

Note: Make sure MongoDB is running on your machine. If not, start it with:
  `mongod`

