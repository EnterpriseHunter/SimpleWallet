# SimpleWallet
Simple Wallet - clear code to review and send ether.
The goal of this wallet is to make most simple and trust tool for sending ether without privacy leak.
You can use it at [Simple wallet page](https://ethercallteam.github.io/SimpleWallet/) or download only one file index.html to your local storage and run in browser for privacy use.

**We are not save your data and not send your private key**

# Instruction

## Node Address
Set here address to your ethereum node. It can be local node or node at [infura.io](https://infura.io/)
For testing we are using this test node (ethereum ropsten) https://ropsten.infura.io/KEnqBsuF7hVHA71fyEwS

## From address
You send ether from this address.

## Private key
To sing transactions you have to input your private key. This is private info. Keep it in safe. Your private key used only for signing transaction

## To address
This address will receive ether after transaction complete

## Gas price in WEI
Gas price can change and depends of ethereum network workload. You can see optimal gas price at [ethgasstation.info](https://ethgasstation.info/). Be carefull this value is in WEI. To set 1 GWEI you need to input 1000000000 (1 and 9 0's). To set 0.1 GWEI need to input 100000000 (1 and 8 0's)

## Gas limit
This parameter limits miners to charge you for transaction mining, default is 30000.

## Ether
Amount ether to send. This value is in ether. If you want to send 1ETH - input 1. If you want to send 0.1ETH input 0.1 and so on.
