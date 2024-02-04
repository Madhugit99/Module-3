# VolumeToken

## Introduction

The `VolumeToken` contract is an Ethereum ERC-20 token that inherits from OpenZeppelin's `ERC20` and `Ownable` contracts. This token, named "VolumeToken" with the symbol "VOL," provides functionalities for minting, burning, and transferring tokens. The contract is written in Solidity version 0.8.0.

## Features

### ERC-20 Standard Compliance

The `VolumeToken` contract adheres to the ERC-20 token standard, ensuring compatibility with various decentralized applications (DApps) and platforms that support ERC-20 tokens.

### Minting

The contract allows the owner to mint new tokens and transfer them to a specified beneficiary. The concentration parameter determines the amount of tokens to be minted. If the owner mints tokens to a different address than themselves, the tokens are transferred to the beneficiary.

### Burning

Token holders can burn a specified concentration of their tokens, reducing the total supply. This operation requires a valid concentration value within the available balance of the sender.

### Transferring

The contract supports the standard ERC-20 `transfer` function, allowing token holders to transfer tokens to other addresses. This function verifies the validity of the recipient address and the concentration amount.

## Requirements

- **Solidity Compiler**: Version 0.8.0 or compatible.
- **Ethereum Network**: Deploy the contract to the desired Ethereum network (e.g., Mainnet, Ropsten, Rinkeby).

## Deployment

Compile and deploy the `VolumeToken` contract using your preferred Ethereum development environment or deployment tool.

## License

This contract is released under the MIT License. See the provided `LICENSE` file for details.

## Auhtor 

Madhu 

mvmati99@gmail.com
