
# Quadrans ERC20 Token

The Quadrans ERC20 Token serve as a collateral to users for the recognition of Masternodes and Miner nodes within the network. Anyone that possesses QDT becomes a Token Holder. With a certain amount of QDT, a Token Holder may activate a Miner node (1000 QDT) or a Masternode (100000 QDT).
They also regulate the distribution of new QDC as a reward for the participation to the network. All Token Holders are rewarded with QDC according to the transactions processed by Quadrans inf rastructure. QDT have been generated in compliance with the standardized Ethereum ERC20 tokens.

  - Tokens supply: **600 million**
  - they cannot be minted or burnt
  - they have no timelock on them.
  - Symbol: **QDT**
  - Contract is deployed on **Ethereum Mainnet** and can be inspected on [etherscan]

Holders may join or leave Quadrans network as they wish and with no restrictions

## Index
* [General Info](#general-info)
* [Used technologies](#used-technologies)
* [Functions](#functions)
* [Structure](#Structure)
* [Screenshot](#screenshot)
* [Install](#install)
* [How it works](#how-it-works)
* [Product Status](#product-status)

## General Info

### Credits

- [OpenZeppelin]

### License
- MIT 

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)




## Used technologies
- Quadrans blockchain
- OpenZeppelin libraries
- EIP20 token standard

## Functions

All basic ERC20 token functions are available

## Structure

This smart contract leverages other OpenZeppelin libraries and smart contracts such as:

- `Roles`
- `PauserRole`
- `MinterRole`
- `SafeMath`
- `SafeERC20`
- `ERC20Detailed`
- `Pausable`
- `IERC20`
- `ERC20Pausable`
- `ERC20Mintable`
- `ERC20Capped`

## Screenshot
- NA

## Install
You do not need to install this token smart contract as it is already in prodiction and _'there can be only one'_. You can find the deployed contract on Ethereum main net here 

https://etherscan.io/token/0x9adc7710e9d1b29d8a78c04d52d32532297c2ef3

There is also a test deploy on **Ropsten** testnet that can be found here

https://ropsten.etherscan.io/address/0xcc5A1bC08aba4B2cb513878E1F097350D4e4cC32

## How it works

See [EIP20](https://eips.ethereum.org/EIPS/eip-20) for further information


## Product Status
The product is: _deployed in production on Ethereum Mainnet_


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [etherscan]: <https://etherscan.io/token/0x9adc7710e9d1b29d8a78c04d52d32532297c2ef3>
   [OpenZeppelin]: <https://github.com/OpenZeppelin/openzeppelin-contracts/tree/master/contracts/token/ERC20>

