## FundMe 

FundMe is a basic test project designed for learning purposes. 
It demonstrates how to interact with smart contracts, deploy them to a blockchain, and leverage Chainlink data feeds for real-time price data. 

### Features
- Chainlink Data Feeds: Integrated Chainlink oracles for fetching real-time price data.
- Deployment Scripts: Scripts for deploying the contract to various blockchains.
- Testing: Unit, mock, fork and integration tests are present
- Helper Configuration: Blockchain-specific configuration for flexible deployment across different environments.
- Price Functions Library: Encapsulated price-related functions in a separate library for clean and reusable code.

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Deploy

```shell
forge script script/DeployFundMe.s.sol
```
