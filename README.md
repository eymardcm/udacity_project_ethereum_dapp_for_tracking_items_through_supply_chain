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
https://rinkeby.etherscan.io/address/0x8e802c9ef712e0fa8cbc44829b58ac1a5ad22029
#### Contract Hash: 
0x7036a54ab7d6d56aed027480b7cef9a73cbfd430d01070965b7e7a6e2be47888
#### Transaction Hash: 
0xfe485c2a16215835ad9fb9684cab1f1a276ed2bac33b957e473efe9b89021cb9

## Versions
Truffle v4.1.13 (core: 4.1.13)
Solidity v0.4.24 (solc-js)

## Instructions for Running Test Cases for the Smart Contract
1.  truffle compile
2.  truffle test

## Instruction for Running the Front End App
1. npm run dev

## Instruction for Deploying the Smart Contract to Rinkeby Testnet
1.  truffle migrate --network rinkeby