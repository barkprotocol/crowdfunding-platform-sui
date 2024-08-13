![Banner](.github/assets/github-banner.png)

# BARK Protocol: SUI-Based Crowdfunding Platform
**Prototype**

Welcome to the BARK Protocol GitHub repository! This repository contains the codebase and documentation for our decentralized crowdfunding platform built on the SUI blockchain. The BARK Protocol aims to provide a secure, scalable, and user-friendly solution for fundraising, leveraging the high-performance capabilities of the SUI blockchain.

## Overview

The BARK Protocol is designed to enhance the efficiency, security, and transparency of fundraising campaigns. Our platform supports multi-currency contributions, integrates decentralized storage solutions, and uses advanced security measures to ensure a reliable and trustworthy experience for users and campaign creators.

### Key Features

- **SUI Blockchain Integration:** Utilizes the high-performance SUI blockchain for fast and secure transactions.
- **Secure Donations:** Donations are made securely using blockchain technology, ensuring transparency and immutability.
- **Automated Token Minting:** Fundraiser tokens are automatically minted and distributed to donors as proof of contribution.
- **Digital Fund Receipts:** Donors receive digital receipts for their contributions, maintaining a verifiable record of transactions.
- **Decentralized Storage:** Employs Arweave/IPFS for durable and censorship-resistant data storage.
- **Smart Contracts:** Automates fundraising processes and enforces campaign rules using SUI’s native programming language.
- **Cross-Chain Functionality:** Integrates Chainlink and PYTH oracles for real-world data integration and enhanced functionality.
- **User-Friendly Frontend:** Built with React.js, providing an intuitive interface for campaign management and donation processing.
- **Wallet Integration:** Supports SUI-compatible wallets for secure authentication and transactions.

## Architecture

### Components

1. **Frontend (React.js):**
   - Dynamic user interfaces for campaign management and donation processing.
   - Integration with SUI Web3 SDK for blockchain interactions.

2. **Backend (SUI Blockchain):**
   - High-performance blockchain network handling transactions and smart contract execution.
   - Smart contracts written in SUI’s native language for campaign automation.

3. **Decentralized Storage:**
   - **Arweave/IPFS:** Secure storage for campaign metadata and media files.

4. **APIs and SDKs:**
   - **SUI Web3 SDK:** Facilitates interaction between the frontend and the SUI blockchain.
   - Third-party APIs for additional functionalities such as identity verification and data aggregation.

5. **Security Components:**
   - **Encryption:** End-to-end encryption for data security.
   - **Authentication:** Secure wallet-based authentication methods.

6. **Oracles and External Integrations:**
   - **Chainlink:** Provides decentralized oracles for real-world data.
   - **PYTH:** Delivers high-fidelity financial market data.

7. **Governance:**
   - Community-driven governance mechanisms for protocol upgrades and policy changes.

8. **Monitoring and Analytics:**
   - Tools for tracking blockchain performance and analyzing user interactions.

### Architecture Diagram

![Architecture Diagram](.github/assets/architecture-diagram.png)

## Use Cases

- **Charity Fundraising:** Non-profits can leverage BARK Protocol for transparent and efficient fundraising, ensuring that donations are used effectively.
- **Project Funding:** Startups and projects can raise funds while providing immediate liquidity for their tokens, enhancing their market presence.
- **Community Initiatives:** Community-driven projects can benefit from automated and transparent fundraising mechanisms.

![screenshot] (./frontend/assets/)
![screenshot] (./frontend/assets/)
![screenshot] (./frontend/assets/)

## Getting Started

To get started with the BARK Protocol, follow the instructions below:

### Prerequisites

- **Node.js:** Ensure you have Node.js and npm installed.
- **SUI-Compatible Wallet:** For interacting with the blockchain.
- **Arweave/IPFS Access:** For decentralized storage.

### Environment Variables

Rename the file `env.local.example` to `env.local` and add the required environment variables in the file:

```
NEXT_PUBLIC_INFURA_IPFS_PROJECT_ID =  
NEXT_PUBLIC_INFURA_IPFS_PROJECT_SECRET = 
NEXT_PUBLIC_INFURA_ProjectAPIKey =  
NEXT_PUBLIC_CLIENT_ID = 
NEXT_PUBLIC_CLIENT_SECRET = 
NEXT_PUBLIC_PROVER_URL = https://prover-dev.mystenlabs.com/v1

NEXT_PUBLIC_REDIRECT_URL = http://localhost:3000/callback

NEXT_PUBLIC_OPENID_PROVIDER_URL = https://accounts.google.com/.well-known/openid-configuration

NEXT_PUBLIC_FULLNODE_URL = https://fullnode.testnet.sui.io:443

NEXT_PUBLIC_PACKAGE_ID = 
```

### Running the App

Start the development server:

```bash
npm run dev
```

Note: This DApp’s smart contract was deployed on the SUI testnet.

### Interacting with the Smart Contract

Navigate to the contract directory:

```bash
cd contract
```

### Testing the Smart Contract

Run tests using:

```bash
sui move test
```

### Compiling the Smart Contract

Build the smart contract:

```bash
sui move build
```

### Deploying the Smart Contract

Publish the smart contract:

```bash
sui client publish --gas-budget 1000000000
```

### SUI Testnet Explorer

View the contract on the SUI Testnet Explorer:

```
https://suiscan.xyz/testnet/object/

## Contributing

We welcome contributions to the BARK Protocol! Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

The MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

The information provided in this repository is for informational purposes only and does not constitute financial, legal, or investment advice. Participants should seek professional guidance before engaging with the BARK Protocol platform. Participation involves risks including market volatility and regulatory changes. By using our platform, you acknowledge and accept these risks.