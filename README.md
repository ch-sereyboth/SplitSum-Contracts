# SplitSum
[![CI](https://github.com/encode-club-solidity-bootcamp-team-11/SplitSum-Contracts/actions/workflows/build.yml/badge.svg)](https://github.com/encode-club-solidity-bootcamp-team-11/SplitSum-Contracts/actions/workflows/build.yml)

### Idea
Web3 bill splitting app

### Description
Split expenses with friends when you go hangouts or your holiday trips. Taking expenses for group purchases and distribute back to the correct parties automatically.

### Goals
- Smart contract for setting parameters at deployment and handling payments from every listed user
- Balancing and simplifying settlements among members
- Prices pegged in a Stablecoin (like USDC)
- Chainlink oracles for price feeds
- Exchanging tokens using Uniswap

<div align="center">
  <a href="images/SplitSum-Wireframe.png">
    <img src="images/SplitSum-Wireframe-Small.png" alt="SplitSum" width="75%">
  </a>
</div>

## Setup

### Run tests

```bash
yarn install
yarn test
```

## Deployment

### Deploy to Hardhat local in-memory network

```bash
yarn hardhat node
yarn deploy:local
```

### Deploy to Metis Goerli Testnet

Setup your deployer wallet in environment variables. Look at the example in `.env.example`

```bash
cp .env.example .env
# Replace placeholders with your keys
```

Deploy to the network

```bash
yarn deploy:metis
```

## Go To

- [Frontend](https://github.com/encode-club-solidity-bootcamp-team-11/SplitSum-Frontend)
- [Backend](https://github.com/encode-club-solidity-bootcamp-team-11/SplitSum)

## License

The software is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
