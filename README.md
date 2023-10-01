# DegenToken

## Description
DegenToken is a Solidity smart contract that implements an ERC20 token with additional functionalities. It allows for minting, transferring, burning, and redeeming items using the token.

## Features
- Minting of tokens
- Transferring tokens
- Burning tokens
- Redeeming items with tokens
- Adding new items with associated prices

### Usage
1. Deploy the `DegenToken` contract to your Ethereum network.
2. Interact with the contract using your preferred Ethereum wallet or a DApp.

## How to Deploy

1. Compile the `DegenToken.sol` file using a Solidity compiler.
2. Deploy the compiled contract to your preferred Ethereum network.

## Contract Details

### `DegenToken` Contract

#### Functions
- `mint(address to, uint256 amount)`: Mints a specified amount of tokens and assigns them to the specified address. Only the contract owner can call this function.
- `transfer(address recipient, uint256 amount)`: Transfers a specified amount of tokens to the recipient address.
- `redeem(uint256 itemId)`: Redeems an item by ID using tokens.
- `checkBalance(address account)`: Checks the token balance of a specified account.
- `burn(uint256 amount)`: Burns a specified amount of tokens, effectively removing them from circulation.
- `addItem(string memory name, uint256 price)`: Adds a new item with a specified name and price. Only the contract owner can call this function.
- `getItemPrice(uint256 itemId)`: Gets the price of a specified item by ID.
- `getItem(address player)`: Gets the inventory count of a specified player.
- `getAllItems()`: Gets an array of all available items.
