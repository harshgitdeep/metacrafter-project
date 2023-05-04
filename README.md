# Metacrafters-Solidity-Project

## MyToken Contract
This Solidity contract defines a custom token with the name "Ether" and abbreviation "Eth". It allows minting and burning of tokens by updating the total supply and balances of addresses.

## Requirements
The contract has public variables to store the token details such as Token Name, Token Abbrv., and Total Supply.
The contract has a mapping of addresses to balances.
The contract has a mint function that takes two parameters, an address, and a value. The function increases the total supply by the given value and updates the balance of the sender's address.
The contract has a burn function that works opposite to the mint function. It destroys tokens by deducting the value from the total supply and the balance of the sender's address.
The burn function has conditionals to ensure that the sender's balance is greater than or equal to the amount being burned.

## Usage
To use this contract, you can deploy it on a Solidity-compatible blockchain network, such as Ethereum. Once deployed, you can call the mint function with an address and a value to increase the total supply and update the balance of the address. Similarly, you can call the burn function with an address and a value to deduct the value from the total supply and the balance of the address.

## License
This code is licensed under the MIT license. See the SPDX-License-Identifier tag in the code for more information.
