# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
npx hardhat help
REPORT_GAS=true npx hardhat test
npx hardhat coverage
npx hardhat run scripts/deploy.js
node scripts/deploy.js
npx eslint '**/*.js'
npx eslint '**/*.js' --fix
npx prettier '**/*.{json,sol,md}' --check
npx prettier '**/*.{json,sol,md}' --write
npx solhint 'contracts/**/*.sol'
npx solhint 'contracts/**/*.sol' --fix
```

# Etherscan verification 

To try out Etherscan verification, deploy the contract to an Ethereum network that's supported by
Etherscan, such as Goerli (the deployment script contains also a verification script). 

In this project, copy the .env.example file to a file named .env, and thene dit it to fill in the details. Enter your 
Etherscan API key, your Goerli node URL (eg from Alchemy), and the private key of the account which will send the 
deployment transaction. With a valid .env file in place, deploy your contract: 

```shell
yarn hardhat deploy --network goerli
```

Then wait for the contract's verification process to complete.
