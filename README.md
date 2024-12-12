# Hardhat Smart Contract Lottery

This repository hosts a decentralized and fully automated lottery system built with Hardhat. It utilizes Chainlink VRF (Verifiable Random Function) for secure randomness and Chainlink Keepers for automated operations, ensuring transparency and autonomy in selecting lottery winners.

## Features

- **Decentralized Automation**: The lottery operates without manual intervention, leveraging Chainlink Keepers for periodic tasks.
- **Secure Randomness**: Ensures fairness in winner selection using Chainlink VRF.
- **Extensive Testing**: Includes unit tests, staging tests, and mock contracts for robust development.
- **Customizable Deployment**: Easily deployable on Ethereum testnets like Sepolia and others.

## Prerequisites

Before starting, ensure the following tools are installed:
- [Node.js](https://nodejs.org/)
- [Hardhat](https://hardhat.org/)
- A Chainlink-compatible wallet (e.g., MetaMask)

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/junaid5598/hardhat-smartcontract-lottery.git
cd hardhat-smartcontract-lottery
```

### Install Dependencies
```bash
yarn install
```

### Environment Setup
Create a `.env` file and add the following keys:
- `PRIVATE_KEY`: Your wallet's private key (testnet only, no real funds).
- `SEPOLIA_RPC_URL`: RPC endpoint URL for the Sepolia network (e.g., from [Alchemy](https://www.alchemy.com/)).

Example:
```plaintext
PRIVATE_KEY=your_private_key
SEPOLIA_RPC_URL=https://sepolia.infura.io/v3/your_project_id
```

## Usage

### Deployment
Deploy contracts to the desired network:
```bash
yarn hardhat deploy
```

### Testing
Run tests to ensure functionality:
```bash
yarn hardhat test
```

### Coverage
Check test coverage:
```bash
yarn hardhat coverage
```

## Running the Lottery

1. **Fund the Contract**: Ensure the contract has enough LINK tokens for Chainlink operations.
2. **Start Lottery**: Use scripts to initiate the lottery.
3. **Draw Winner**: Automatically triggered by Chainlink Keepers, or manually for testing.

## Contributions

Contributions are welcome! Please fork the repository, make changes, and submit a pull request.
```

Let me know if further modifications are needed!
