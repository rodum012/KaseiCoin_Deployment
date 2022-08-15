# KaseiCoin_Deployment

The creation of a token called "KasseiCoin" that is funded using a crowdsale.

---

## Technologies

This application is written in Solidity 0.5.5 and is deployed on the [Remix IDE](https://remix.ethereum.org/) using [Metamask](https://metamask.io/) and [Ganache](https://trufflesuite.com/ganache/).

---

## Installation Guide

Prior to running this application, naviagte to the website for Remix IDE where the code is deployed at https://remix.ethereum.org/. Additionally, set up a Metamask and local Ganache wallet.

---

## Usage

In order to launch the application, navigate to the KaseiCoin_Deployment folder that contains all of the code for this application, and then open both the KaseiCoin.sol and KaseiCoinCrowdsale.sol files in the Remix IDE:


Once the files are open in the Remix IDE, navigate to the'compiler' tab and make sure the compiler is set to 0.5.5, and then compile both files. Next, navigate to the 'Deploy and Run Transactions tab' and make sure the contract is set to KaseiCoinCrowdsaleDeployer. From there, enter the name and symbol of the coin and input the wallet address that will be used to receive the crowdsale funds. Click transact to deploy the application. Once deployed, naviagte to the deployed contracts section, and click both contracts in order to copy their respective addresses and proceed to past these addresses one at a time into the At Address box followed by clicking the At Address button to link the addresses to the contracts. Now scroll down to see the various functionalities of the contracts including sending tokens and minting more.

Below, you can see examples of sending transactions of the token and the resulting account balances and total wei raised in the crowdsale being viewed: 

Transaction of 20 wei:

![20_trans](Images/20_trans.png)

Transaction of 30 wei:

![30_trans](Images/30_trans.png)

Total Resulting Balance View:

![balance_total](Images/balance_total.png)

Total Supply View:

![supply_total](Images/supply_total.png)

Wei Raised Total View:

![wei_total](Images/wei_total.png)

---

# Evaluation Evidence 

Below is the evidence that all contracts were compiled correctly and deployed:

KaseiCoin Compilation:

![compile_1](Images/compile_1.png)

KaseiCoinCrowdsale original Compilation:

![compile_2](Images/compile_2.png)

KaseiCoinCrowdsale final Compilation:

![compile_3](Images/compile_3.png)

Deployment of KaseiCoin and resulting balance of wallet used:
![account_link](Images/account_link.png)
![link_balance](Images/link_balance.png)

Linking of the contract addresses:
![address_link](Images/address_link.png)
---

## Contributors

Robby Odum

Email: rodum012@gmail.com

---

## License

MIT

