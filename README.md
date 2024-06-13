# Mint_Token

This is the final project assesment of Eth Proof Beginner Course. 

## Description

This is a Solidity based project that implements a smart contract. Name of the token is Madcoin and its abbrevation is 'MDC'. The contract allows for the minting and burning of tokens.
## Getting Started

### Executing program

* Download the assesment file in the local computer
* Run this file on remix editor.



## Functions

mint: A function that increases the total supply of tokens and updates the balance of a specified address.
<br>
burn: A function that decreases the total supply of tokens and updates the balance of a specified address, with a condition to ensure the address has enough tokens to burn.
`

# Parameters:
Address: The address from which the tokens will be burned.
Value: The amount of tokens to be burned.
Description: This function decreases the totalSupply by the _value specified and updates the balance of _address by the same amount. It includes a check to ensure that the Address has enough tokens to burn; otherwise, it will revert the transaction with an error.


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
