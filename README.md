# PDX | 'Porter' Decentralized Exchange
This project is a fully functional decentralized exchange which operates on Ethereum (Kovan ;-) testnet actually ). Maybe one day it will be a live project on Ethereum mainnet. The token available for trading is called PTV | Porter TV token in honor of my family company [Porter TV](http://portertv.com). The tokens aren't worth anything it's all just for kicks.

What the hell does decentralized exchange mean? All trades are integrated into the Smart Contract. The trades are executed by code on the Ethereum blockchain and not code on some centralized server somewhere. This literally means you are interacting and executing trades that are completely verifiable on the blockchain. Yes you are connecting to a website that is centralized ***but*** the actual trades are being handled by the smart contract on the blockchain.

## Future Development
Looking to integrate other tokens to be able to trade multiple tokens within Ethereum.  

## Logic behind the structure

 - [x] First off, organization played a key roll in this project. Organizing code into intuitive contracts that are compartmentalized.  
 - [x] Standardized code was implemented for various features by **OpenZepplin** such as an *ERC-20 token*, *SafeMath* for any for any numbers(`uint`). One of the reasons for SafeMath is to thwart under/overflow.  *Pausible* was added to grant the `msg.sender` the ability to freeze various functions in the Exchange.
 - [x] A `revert` was added in the event Ether is sent accidentally to the smart contract.
 - [x] Declaring `view` for functions that do not change the state of the contract.
 - [x] Declaring `Private` for functions that are not intended to be called outside of the contract (in contrast  enabling a function to be called with a public getter)

## How to use?
If you are not familiar with Ethereum blockchain I suggest you check out their main page [Ethereum](https://www.ethereum.org/).

This project is currently deployed to the Kovan testnet. See  [testnet](https://kovan-testnet.github.io/website) page for more information on what is Kovan.
How do I get Ethereum on Kovan testnet?! Get free Ethereum on Kovan [here](https://faucet.kovan.network)

Live link [here](https://flamboyant-lovelace-7f1148.netlify.com/)

Note: Metamask extension is required if you want to interact and make sells/trades. 
