# Voting Smart Contract 
![W_msp2017030040-750x500-750x500](https://github.com/krritik01/Project-Voting-System-using-Solidity/assets/98963769/8301ba4b-16f7-42d6-98cc-abea7221a643)
## Introduction
This repository contains a smart contract written in Solidity for conducting voting operations. The smart contract enables users to start and stop voting sessions, add and remove their votes, and retrieve voting results. This README provides an overview of the code, its functionality, and how to use it.

### ➡Smart Contract Overview
• The "voting.sol" smart contract defines a simple voting system with the following features:

• Voting Session Control: Users can start and stop the voting session by calling startVoting() and stopVoting() functions, respectively.

• Vote Casting: Users can cast their votes by calling the addVote(address receiver) function. Each vote consists of the voter's address, the candidate's address (receiver), and a timestamp.

• Vote Removal: Users can remove their votes by calling the removeVote() function.

• Vote Retrieval: Users can retrieve their vote by calling the getVote(address voterAddress) function, which returns the address of the candidate they voted for.

• Events: The contract emits events for critical actions, including starting and stopping voting sessions, adding and removing votes, and updating vote details. These events can be monitored to track the contract's activity.

### ➡How to Use
To use this smart contract, follow these steps:

• Deploy the contract to a compatible Ethereum blockchain network (compatible with Solidity version 0.8.2 to 0.9.0).

• Use a web3-compatible application or tool to interact with the deployed contract. You can call the functions startVoting(), stopVoting(), addVote(address receiver), removeVote(), and getVote(address voterAddress) as needed.


## Acknowledgements
Decentralize Portfolio is built using the following technologies:
 - [Solidity](https://docs.soliditylang.org/en/v0.8.21/)
 - [Ethereum](https://ethereum.org/en/learn/)
 - [Remix IDE](https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.18+commit.87f61d96.js)
 
## License
This code is open-source and available under the MIT License. See the [LICENSE](https://choosealicense.com/licenses/mit/) file for more details








