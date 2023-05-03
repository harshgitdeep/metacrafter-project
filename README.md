<b>MyToken Contract</b>
This Solidity smart contract implements a basic ERC-20 compatible token called MyToken. It has the following features:

Public variables to store the details about the token, including the token name, token abbreviation, and total supply.
A mapping of addresses to balances to keep track of the token balance for each address.
A mint function that increases the total supply of the token and the balance of the specified address.
A burn function that decreases the total supply of the token and the balance of the specified address.
Requirements
Solidity version 0.8.18 or later.
This contract is licensed under the MIT License (SPDX-License-Identifier: MIT).
Installation
To use this contract, you can simply copy the code and deploy it to a compatible Ethereum network using your preferred development tools.

Usage
After deploying the contract, you can interact with it by calling the mint and burn functions. The mint function takes two parameters: an address and a value. It increases the total supply of the token by that value and increases the balance of the specified address by that amount. The burn function works in the opposite way. It takes an address and a value, and it decreases the total supply of the token and the balance of the specified address by that amount.

License
This project is licensed under the MIT License (SPDX-License-Identifier: MIT). Please see the LICENSE file for more information.
