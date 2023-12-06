# NFT with metadata
For this exercise you are asked to program a smart contract using Solidity.

This smart contract will be used to create NFTs that hold additional metadata. Theses NFTs represent real-world assets.

## Requirements 
Your smart contract must satisfy the following requirements:
- The NFTs respect the ERC 721 standard.
- An NFT can have a parent NFT (using metadata). This enables us to create a hierarchy of NFTs.
- Only the owner of the contract has the right to mint NFTs (use the ownable interface from openzeppelin).
- An NFT holds additional metadata:
  - a description of the NFT.
  - a parent field that holds the token id of the parent NFT (if the NFT is a child).
  - an owner field that holds the public address of an account that owns this NFT. (only the contract owner can mint NFTS but can attribute this field to another account to indicate who is the owner).
- a method to modify an NFT's metadata.
- a method to read an NFT's metadata.
- a method to get the children NFTs (token ids) of a given NFT.

Provide some testing functions that call the methods of your smart contract and check the results.

## How to proceed
Clone this repo and when you are done, please provide us with a link to your repo containing the solution. Your repo must have a readme indicating the steps needed to deploy and test your smart contract.
