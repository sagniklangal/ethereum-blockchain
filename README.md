# Decentralized Agriculture Supply Chain Systems

This decentralized application regulates the agriculture supply chain by allowing the stakeholders to update and read the farm product status on Ethereum Blockchain.

The application is designed to enable easy and error-proof tracking of farm products from the farmer to the consumer.

## Features

- Users can fetch details of existing Products and Farms and also feed details of new Products and Farms.

![Agriculture Supply Chain DApp](./Screenshots/Fetch%20Product%20Details.png)

- At the different stages of the supply chain, the concerned stakeholders can update and trace the status of the shipment. 

![Agriculture Supply Chain DApp](./Screenshots/TraceProduct.png)

- The entire transaction history is logged and the transactions can be validated on Etherscan using the Transaction ID.

![Agriculture Supply Chain DApp](./Screenshots/TransactionHistory.png)

## Set Up

- Pre-requisites: Metamask, Ganache, Truffle Environment.
- Clone the repository and run ```npm i``` to install the required dependencies.
- Run ```truffle compile``` and then ```truffle migrate``` to instantiate the Smart Contracts.
- Run ```npm run start``` to start the application.

## Tech Stack

This Supply Chain project combines various different technologies:

- **Node and Express** - Backend server and APIs
- **React** - Client-side application
- **Solidity** - Smart Contracts for the Ethereum Blockchain
- **Ethereum** - Platform for decentralized apps (DApps)
- **Truffle** - Development environment for Ethereum
