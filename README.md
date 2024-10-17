# Foundry FundMe Cyfrin

## Project Structure

```plaintext
foundry-fundme-cyfrin/
├── .github/
│   └── workflows/
│       └── test.yml
├── .gitignore
├── .gitmodules
├── foundry.toml
├── lib/
│   ├── chainlink-brownie-contracts/
│   ├── forge-std/
│   └── foundry-devops/
├── Makefile
├── README.md
├── script/
│   ├── DeployFundMe.s.sol
│   ├── DeployStorageFun.s.sol
│   ├── HelperConfig.s.sol
│   └── Interactions.s.sol
├── src/
│   └── exampleContracts/
│       ├── FunWithStorage.sol
│       ├── FundMe.sol
│       └── PriceConverter.sol
├── test/
│   ├── integration/
│   │   └── InteractionsTest.t.sol
│   ├── mock/
│   │   └── MockV3Aggregator.sol
│   └── unit/
│       ├── FundMeTest.t.sol
│       └── ZkSyncDevops.t.sol
```

## Running Tests

To run the tests, execute the following command:

```bash
forge test
```

## Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
