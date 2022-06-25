# Hardhat Simple Storage

This project is built using both javascript and typscript

Commands I used in this project:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.ts
npx hardhat help
```
```shell
<!-- Added by me -->
<!-- commanline commands -->
yarn hardhat test
yarn hardhat test --grep store <!-- to invoke test with store word in it -->
yarn add --dev hardhat-gas-reporter
yarn add --dev solidity-coverage
yarn hardhat coverage <!-- how much of the code is covered with testing -->
yarn add --dev @typechain/ethers-v5 @typechain/hardhat @types/chai @types/node @types/mocha ts-node typechain typescript <!-- to convert project to use typescript -->
yarn hardhat run scripts/deploy.ts --network hardhat
yarn hardhat typechain <!-- to generate typescript definition for the contracts tha I made -->
```

# Environment Variables To Set
RINKEBY_RPC_URL,
PRIVATE_KEY,
EHERSCAN_API_KEY,
COINMARKETCAP_API_KEY,
