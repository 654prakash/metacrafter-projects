# ERC20 and Vault Contracts

## Overview

This repository contains two smart contracts implemented in Solidity:
1. **ERC20 Contract**: A standard ERC20 token implementation.
2. **Vault Contract**: A vault for securely storing and managing ERC20 tokens.

## Contracts

### ERC20 Contract

The ERC20 contract is a standard implementation of the ERC20 token, which includes basic functionalities such as transferring tokens, approving allowances, and querying balances.

#### Features
- **Total Supply**: Returns the total supply of the tokens.
- **Balance Of**: Returns the token balance of a specific address.
- **Transfer**: Transfers tokens to a specified address.
- **Approve**: Allows another address to spend a specified amount of tokens on behalf of the token owner.
- **Transfer From**: Transfers tokens from one address to another using an allowance mechanism.
- **Allowance**: Returns the remaining number of tokens that an address is allowed to spend on behalf of the token owner.

### Vault Contract

The Vault contract is designed to securely store ERC20 tokens. Users can deposit and withdraw tokens, and the contract keeps track of each user's deposited balance.

#### Features
- **Deposit**: Allows users to deposit ERC20 tokens into the vault.
- **Withdraw**: Allows users to withdraw their deposited ERC20 tokens from the vault.
- **Balance Of**: Returns the deposited token balance of a specific user.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenZeppelin for their ERC20 implementation
- Ethereum community for continuous support and resources
