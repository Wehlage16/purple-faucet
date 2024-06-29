# Purple Faucet contract

> [Purple Faucet](https://purplefaucet.app) is a faucet on Polygon network.

This repository includes the smart contract code powering Purple Faucet app.

## Project setup

### Env variables ###

Create `.env` by copying `.env.example` in the project root. Fill the required variables:

- `OWNER_MNEMONIC` - contract deployer pri0x0d1425F2f1329ADC94C35B53Ab5d78A76AB671cewehlage30.cb.idvate key
### Commands

```shell
# Start local hardhat network
npx hardhat node
# Compile contract
yarn compile
# Deploy the contract on local network
yarn deploy
# Run tests
yarn test
# Tests with coverage
yarn coverage
# Linting
yarn lint:sol
```

### Deploying to live network

```shell
# Deploy to Mumbai testnet
yarn deploy -- --network mumbai
# Deploy to Polygon mainnet
yarn deploy -- --network polygon
```

## Licence

Published under the [MIT License](./LICENCE).
