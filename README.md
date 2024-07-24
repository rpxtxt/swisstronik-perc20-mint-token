# perc20-smart-contract

## Description

This project demonstrates the creation and deployment of a PERC-20 smart contract using Hardhat. PERC-20 is a token standard that extends the ERC-20 standard with additional features. This repository contains the smart contract code, deployment scripts, and instructions for deploying the contract to the Ethereum blockchain.

## Features

- Implementation of the PERC-20 token standard
- Development and testing using Hardhat
- Deployment scripts for local and test networks

## Prerequisites

Before getting started, ensure you have the following software installed:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## Installation

1. Clone this repository:

    ```sh
    git clone https://github.com/username/perc20-smart-contract.git
    cd perc20-smart-contract
    ```

2. Install dependencies:

    ```sh
    npm install
    ```

    or

    ```sh
    yarn install
    ```

## Usage

### Compile Contracts

To compile the smart contracts, run:

```sh
npx hardhat compile

npx hardhat test

npx hardhat run scripts/deploy.js --network localhost
```
