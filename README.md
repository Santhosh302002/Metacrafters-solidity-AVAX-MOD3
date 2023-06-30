# MyToken

MyToken is a simple ERC20 token contract implemented in Solidity. It extends the ERC20 contract from the OpenZeppelin library. This contract allows for the creation, minting, burning, and transferring of tokens.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Prerequisites

- Solidity compiler version ^0.8.0
- OpenZeppelin library

## Getting Started

To get started with this contract, follow the instructions below:

1. Install the Solidity compiler, if you don't have it already.
2. Install the OpenZeppelin library by running the following command:
   ```
   npm install @openzeppelin/contracts
   ```
3. Compile the contract using the Solidity compiler.
4. Deploy the contract to an Ethereum network of your choice.

## Contract Details

### MyToken

The `MyToken` contract is an ERC20 token contract. It inherits from the `ERC20` contract provided by OpenZeppelin. This contract allows the contract owner to mint and burn tokens.

#### Constructor

The constructor of the `MyToken` contract takes three parameters: `_name`, `_symbol`, and `_initialSupply`. It initializes the token's name, symbol, total supply, and the contract owner.

#### Modifiers

- `onlyOwner`: This modifier restricts certain functions to be called only by the contract owner.

#### Functions

- `mint`: This function is used to mint new tokens and assign them to a specified account.
- `burn`: This function is used to burn tokens from a specified account.
- `transfer`: This function is used to transfer tokens from one account to another.
- `balanceOf`: This function returns the token balance of a specified account.

## Usage

To use this contract, follow these steps:

1. Deploy the `MyToken` contract to an Ethereum network.
2. Call the `mint` function to create new tokens and assign them to an account.
3. Call the `burn` function to burn tokens from an account.
4. Call the `transfer` function to transfer tokens from one account to another.
5. Call the `balanceOf` function to check the token balance of an account.

**Note:** The `onlyOwner` modifier ensures that only the contract owner can perform certain actions.

## Contributing

L Santhosh Kumar

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
