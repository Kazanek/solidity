# solidity

1. Intro page 
2. Obsah
- Záměr, teorie, příklad, editor , test

// Events
Events are a way for your contract to communicate that something happened on the blockchain to your app front-end, which can be 'listening' for certain events and take action when they happen.

Tenderly
- Notifications listen - tooling

// refers to the address of the person (or smart contract) who called the current function.
Using msg.sender gives you the security of the Ethereum blockchain — the only way someone can modify someone else's data would be to steal the private key associated with their Ethereum address.
msg.sender

// require
For that we use require. require makes it so that the function will throw an error and stop executing if some condition is not true:

// Inheritancem, using visual

// Storage - Permanently on blockchain
// Memory temporary

// Gas - View functions, Storage is Expensive

// Payable - pay to function
// Withdraw from contract


3. Hard hat
// npm init
// npm install --save-dev hardhat
// npx hardhat
// sample project, install dependencies
// structure - script, contracts

4. Factory
Truffle 

ALCHEMY_KEY=wNWkJfnfVMLDtzxM5DXsB3-D424fFVtp
ALCHEMY_URL=https://polygon-mumbai.g.alchemy.com/v2/wNWkJfnfVMLDtzxM5DXsB3-D424fFVtp
PRIVATE_KEY=0d6c13fe5fed644dfa02512d4bffde9453dcb48873afb0b0a4c0cebce160c279

pragma solidity >=0.7.0 <0.9.0;

contract 