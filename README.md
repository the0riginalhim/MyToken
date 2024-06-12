# MyToken Smart Contract

This repository contains a simple ERC-20 like token smart contract written in Solidity. The contract includes basic functionalities such as minting and burning tokens. 

## Project Description

The `MyToken` contract allows users to mint and burn tokens. It keeps track of the total supply of tokens and the balances of each address. The contract includes the following functionalities:
- **Token Details:** Public variables to store token name, abbreviation, and total supply.
- **Balances:** A mapping of addresses to their token balances.
- **Minting:** A function to increase the total supply and the balance of a given address.
- **Burning:** A function to decrease the total supply and the balance of a given address, with checks to ensure the address has enough tokens to burn.

## Requirements

To deploy and interact with this smart contract, you need:
- [Solidity ^0.8.0](https://docs.soliditylang.org/)
- [Remix IDE](https://remix.ethereum.org/) or a local development environment with [Truffle](https://www.trufflesuite.com/truffle) or [Hardhat](https://hardhat.org/).

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/mytoken-contract.git
   cd mytoken-contract
2. Open the project in Remix IDE or your preferred Solidity development environment.

   Usage
Deploy the Contract:

1. Open the contract in Remix IDE or your local development environment.
2. Compile the contract.
3. Deploy the contract to your desired Ethereum network (e.g., a local blockchain, testnet, or mainnet).
4. Mint Tokens:

5. Call the mint function with the address and amount of tokens to mint.
   
Burn Tokens:

Call the burn function with the address and amount of tokens to burn, ensuring the address has enough balance.
