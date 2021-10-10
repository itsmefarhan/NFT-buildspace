# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

## Run app
- Clone this repo and run **npm install**
- Create **.env** file at root and add **STAGING_ALCHEMY_KEY** and **PRIVATE_KEY**
- Get Alchemy key from alchemy project and private key is from your metamask a/c private key

## Deploy
- npx hardhat run scripts/deploy.js --network rinkeby