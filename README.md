# Blockchain Voting Application

This is a decentralized voting app built in solidity smart contract using ReactJS.

## Project Structure

The project structure is created with this command:

```shell
npx hardhat
```

which creates the following structure:

- `contracts/`: This directory contains the Solidity smart contract files.
- `scripts/`: This directory contains additional scripts for interacting with the smart contracts.
- `src/`: This directory contains the ReactJS frontend code.
  - `components/`: This directory contains reusable React components.
  - `pages/`: This directory contains the main pages of the application.
  - `utils/`: This directory contains utility functions.
- `test/`: This directory contains the tests for the smart contracts.

## Installation

After you cloned the repository, you want to install the packages using

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Run the following commands to compile and upload the contract.

```shell
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. You can also use another blockchain by writing the blockchain's endpoint in hardhat-config.

Once you have pasted your private key and contract address in the .env file, simply run command

```shell
npm start
```
