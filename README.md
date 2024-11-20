## FundMe 

**FundMe is a basic test project for learning purposes.**

- Chainlink data feeds is implemented. 
- There are scripts for deploying and interacting programatically with the contract.
- As well as there is a helperConfig so we can pass a blockchain specific info.
- Testing consists of unit tests, scripts interactions tests and mock for testing locally with anvil.
- Price funtions are in a library.

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
