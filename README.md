# Metacrafters-Solidity-Project

## MyToken Contract
This Solidity contract defines a custom token with the name "Ether" and abbreviation "Eth". It allows minting and burning of tokens by updating the total supply and balances of addresses.

## Requirements
1. The contract has public variables to store the details about the coin:
   - `tokenname`: The name of the token.
   - `tokenabriv`: The abbreviation of the token.
   - `supply`: The total supply of the token.

2. The contract has a mapping of addresses to balances:
   - `balances`: Maps addresses to their respective token balances.

3. The contract has a `mint` function:
   - Parameters: `address` - The address to mint tokens for, `value` - The number of tokens to mint.
   - Description: Increases the total supply by the specified amount and increases the balance of the sender address by that amount.

4. The contract has a `burn` function:
   - Parameters: `address` - The address to burn tokens from, `value` - The number of tokens to burn.
   - Description: Decreases the total supply by the specified amount and decreases the balance of the sender address by that amount.

5. The `burn` function includes conditionals to ensure that the balance of the sender is greater than or equal to the amount to be burned.

## Usage
1. Deploy the contract to a Solidity-compatible blockchain network.
2. Interact with the contract using the following functions:

   - `mint(address _address, uint a)`: Mints `a` tokens and assigns them to the `_address` provided. Increases the total supply and the balance of the `_address`.

   - `burn(address _address, uint a)`: Burns `a` tokens from the balance of the `_address` provided. Decreases the total supply and the balance of the `_address`.

## Authors
@harshgitdeep

## License
This code is licensed under the MIT license. See the SPDX-License-Identifier tag in the code for more information.
