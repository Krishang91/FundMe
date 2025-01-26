# FundMe

FundMe is a decentralized crowdfunding application built on Ethereum using Solidity. It allows users to send ETH to the contract and enables the contract owner to withdraw the funds securely.

## Features
- Accept ETH contributions from users.
- Allow only the owner to withdraw funds.
- Use Chainlink Oracles for ETH to USD price conversion.

## Prerequisites
- [Node.js](https://nodejs.org/)
- [Hardhat](https://hardhat.org/)
- Ethereum wallet (e.g., MetaMask)

## Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Krishang91/FundMe.git
   cd FundMe
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Compile the contracts:**
   ```bash
   npx hardhat compile
   ```
4. **Deploy the contract:**
   ```bash
   npx hardhat run scripts/deploy.js --network <network-name>
   ```

## Usage
- Use the `fund()` function to contribute ETH.
- Use the `withdraw()` function to withdraw funds (only the owner).

## Testing
Run tests to ensure the contract works as expected:
```bash
npx hardhat test
```

## License
This project is licensed under the [MIT License](LICENSE).
