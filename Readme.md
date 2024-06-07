# MyToken

This is a simple ERC20-like token implemented in Solidity.

## Contract Details

The contract is named `MyToken` and it has the following features:

- Public variables that store the details about the token (Token Name, Token Abbreviation, Total Supply)
- A mapping of addresses to balances
- A `mint` function that increases the total supply and the balance of the sender
- A `burn` function that decreases the total supply and the balance of the sender, provided the sender has enough balance

## Functions

### `mint(address _address, uint256 value)`

This function mints new tokens. It increases the total supply by the `value` and increases the balance of the `_address` by the same `value`.

### `burn(address _address, uint256 value)`

This function burns tokens. It decreases the total supply and the balance of the `_address` by the `value`, provided the `_address` has enough balance to burn.

## Usage

To use this contract, deploy it to a Ethereum-compatible network using a tool like Truffle or Hardhat.

## License

This project is licensed under the MIT License.