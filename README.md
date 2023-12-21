# PrimeEstate 
PrimeEstate is a decentralized real estate platform built on the Ethereum blockchain, utilizing smart contracts and web3 technology. This platform allows users to list, buy, and transfer ownership of properties using cryptocurrency, specifically through the MetaMask wallet and goes through the entire process of a real estate transaction.

## Authors

- [@Souvik3469](https://github.com/Souvik3469)(Souvik Sen)

<!--
## Prototype Demo 
https://tender-vault-frontend.vercel.app
-->

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)

### Prerequisites

- Ensure you have MetaMask installed on your web browser.
- Connect your MetaMask wallet to the Ethereum Ropsten test network for testing purposes.

## Features
### Listed Properties
![Listed](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/home1.png)

### Property Metadata
![Details](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/details1.png)
## Note: Initially all Accounts have 10000 ETH.
### Deposit Earnest
- Buyer deposits earnest money or down payment.
![Deposit1](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/depositearnest.png)
- Buyer confirms down payment.
![Deposit2](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/approveearnest.png)

### Inspect and Evaluate
- Inspector approves the property and updates inspection status.
![Inspect1](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/updateinspection.png)

### Lending
- The lender approves and lends the remaining amount for the property.
![Lending1](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/approvelend.png)
- Lender confirms payment.
![Lending2](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/confirmlending.png)

### Selling and Tranfer Ownership
- The seller approves the sale.
![Seller1](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/approvesale.png)
- Tranfers Ownership.
![Seller2](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/tranferownership.png)
- Ownership Transferred.
![Seller3](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/owned.png)

### Wallet Status
#### Buyer
![BuyStatus](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/buyerstatus.png)
#### Lender
![LendStatus](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/lenderstatus.png)
#### Inspector
![InspectStatus](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/inspectorstatus.png)
#### Seller
![SaleStatus](https://github.com/Souvik3469/RealEstateBlockchain/blob/main/public/sellerstatus.png)


<!--
## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Run tests
`$ npx hardhat test`

### 4. Start Hardhat node
`$ npx hardhat node`

### 5. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`

-->
