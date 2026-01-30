Blockchain Voting System

A blockchain-based electronic voting (E-Voting) system that ensures transparency, security, and immutability using Ethereum smart contracts.

Build & Run Setup
# Install dependencies
npm install

# Start the development server
npm start


The application runs at:

http://localhost:3000

Environment Configuration

Create a .env file in the root directory with the following variables:

EMAIL=your_email_id
PASSWORD=your_email_password


These credentials are used to send notifications to candidates and voters.

Prerequisites

Node.js

Required version: v11.14.0

Other versions are not tested and may cause issues.

MongoDB

Must be running locally at:

mongodb://localhost:27017


MetaMask Extension

Install from: https://metamask.io/download.html

Connect MetaMask to the Rinkeby Test Network.

Obtain test Ether from: https://faucet.rinkeby.io

Technology Stack

Blockchain: Solidity, Web3.js

Frontend: Next.js, Semantic UI React

Backend: Node.js, Express.js, MongoDB

File Storage: IPFS

Application Workflow

Company registers and logs in.

Company creates an election.

Company adds candidates and voters.

Candidates and voters receive credentials via email.

Voters log in and cast their vote using MetaMask.

Smart contract records votes immutably.

Winner is announced and notified by email.

Screenshots
Homepage

Company Login

Create Election

Dashboard

Candidate List

Candidate Registration Email

Voter List

Voter Registration Email

Voter Login

Successful Voting

Unsuccessful Voting

Winner Notification Email

Notes

Ensure MetaMask is connected before voting.

MongoDB must be running before starting the server.

Use only test Ether (Rinkeby network).

Do not use real credentials for production.

License

This project is for educational and research purposes only.
