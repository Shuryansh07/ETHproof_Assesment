# MyToken Smart Contract
This Solidity smart contract defines a basic token called TechyBling (abbreviated as TB). It includes functionalities to mint and burn tokens, and it maintains a record of balances for each address.

# Contract Overview
The MyToken contract includes the following features:

Public Variables: Token name, abbreviation, and total supply.\
Mapping: To keep track of balances for each address.\
Mint Function: To create new tokens.\
Burn Function: To destroy tokens.\
# Contract Details
# Public Variables
tokenName: The name of the token (TechyBling).\
tokenAbbrv: The abbreviation of the token (TB).\
totalSupply: The total supply of the token.\
# Mapping
balances: A mapping from addresses to their token balances.
# Functions
"mint"\
This function increases the total supply of the token and updates the balance of the specified address.
"burn"\
This function decreases the total supply of the token and updates the balance of the specified address, provided the address has enough tokens to burn.
# License
This project is licensed under the MIT License.
