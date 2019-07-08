# Architect a Supply Chain: Fair Trade Coffee
This repository contains an ethereum blockchain solution for Fair Trade Coffee.  The appication is designed to record the creation of coffee product from raw materials through to the consumer.  The consumer is able to verify their coffee's authenticity through validation of the blockchain.

## Content
In the /diagrams/ folder you will find the following UML diagrams:

Activity diagram (mapping out the activities of each participant)
Sequence diagram (mapping out the functions that will be used and the sequence of them)
State diagram (mapping out the state changes to the item(s) being tracked)
Data diagram (mapping out the structure of our smart contract and their inheritance)
## Libraries
The Roles library is used which allows simple creation and management of different roles, and then provides access controls for these.

#### Contract Address: 
https://rinkeby.etherscan.io/address/0xec59189ce859f5b07e852db0d81315c7c7377857
#### Contract Hash: 
0x3e9ca69e205a3b7416d72b450a83a7d61f89a6c994c2bb759b8a25919552520b
#### Transaction Hash: 
0x0b1abe0170c4c6cf521dbb3a3f6b48d2497d98a08d419fee630d840ef5920828

## Versions
Truffle v4.1.13 (core: 4.1.13)
Solidity v0.4.24 (solc-js)

## Instructions for Testing the Smart Contract
1.  truffle compile
2.  truffle test

## Instruction for Deploying the Smart Contract to Rinkeby Testnet
1.  truffle migrate --network rinkeby

## Instruction for Running the Front End App
1. npm run dev