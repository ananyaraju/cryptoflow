# CryptoFlow

CryptoFlow is a blockchain-based e-commerce website that enables any user with MetaMask to participate in an open trading system where they can buy/sell products for a fixed price or engage in auctions.
It uses Pinata IPFS to store meta-data hence, decreasing gas fees while increasing transcation speed.

## Built With
* React
* Solidity
* Node JS
* Pinata IPFS
* Bootstrap

## Getting Started

1. make '.env' file

2. enter following data in .env file

```
REACT_APP_PINATA_KEY = "<pinata key>"
REACT_APP_PINATA_SECRET = "<pinata secret>"
```

3. npm install

4. deploy script only ONCE by running following command 

```
npx hardhat run --network goerli scripts/deploy.js
```

5. npm start
