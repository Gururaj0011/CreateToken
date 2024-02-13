# BeneficiaryToken 

## Overview

BeneficiaryToken is an Ethereum ERC-20 token smart contract written in Solidity. This token contract extends the functionality of the OpenZeppelin ERC20 implementation and includes additional features such as token minting, burning, and ownership control. The contract is named "BeneficiaryToken" and has the symbol "BFT".

## Features

### Minting

The `mintTokens` function allows the owner of the contract to mint new tokens and allocate them to a specified beneficiary. This feature can be useful for token distribution, rewards, or any other scenario where new tokens need to be created.

### Burning

Token holders can burn their own tokens using the `burnTokens` function. This allows users to reduce their token balance, and the burned tokens are permanently removed from circulation.

### Token Transfer

The standard ERC-20 `transfer` function is extended to include additional checks for the validity of the transfer. The `transferTokens` function ensures that the specified beneficiary is valid, the transfer value is positive, and the sender has sufficient balance.

## Requirements

- Solidity compiler version 0.8.0 or higher.
- OpenZeppelin contracts library version compatible with the specified Solidity version.

## License

This smart contract is released under the MIT License. See the SPDX-License-Identifier at the top of the contract file for details.
##Author 

Gururaj B M 

gururaj48103@gmail.com

