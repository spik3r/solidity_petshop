# Petshop 

> A Solidity example project

## Requirements

``` bash
- Node
- npm install -g truffle
- Ganache: http://truffleframework.com/ganache
- MetaMask: https://metamask.io/
```

## Local Ethereum network commands
```
truffle compile
truffle migrate
truffle test
```

## MetaMask Setup
- Click Import Existing DEN.
- In the box marked Wallet Seed, enter the mnemonic that is displayed in Ganache.
- Connect MetaMask to the blockchain created by Ganache. Click the menu that shows "Main Network" and select Custom RPC.
- In the box titled "New RPC URL" enter http://127.0.0.1:7545

## Start Frontend

``` bash
# Start local webserver
npm run dev
```

For a more detailed explanation check the tutorial: http://truffleframework.com/tutorials/pet-shop
