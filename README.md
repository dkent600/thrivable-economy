# Thrivable Economy
A Refi economic system that emerges regenerative impacts, initially to target the food economy in the Machuca River Valley, a bioregion in Costa Rica.

I have created this project on a Windows 11 machine using VSCode and Powershell.  I haven't tried installing it and running the scripts in WSL or on a Linux machine.

## Hardhat

Comparing Hardhat to Remix and Foundry, Hardhat is an easier integration with things like Typescript, Ethers.js (or Viem), VSCode and Windows, while being at a professional level and helping to stay close to Web3.

https://hardhat.org/

### Typescript

Using the TYpescript version of Hardhat.

### Viem

Small and cleaner version of ethers.js, used by Hardhat.

https://viem.sh/

### Hardhat Ignition

Using it for configuring deployments.

### Hardhat Extension for Visual Studio Code

Using it to facilitate writing quality solidity.

### Hardhat Chai Matchers

Using it for its Ethereum-specific enhancements to the Chai test assertion library.

## Scripts

`npm run clean` -- install or reinstall

`npm run compile` -- compile the contracts

`npm run test` -- test the contracts against the local hardhat node

`npm run deploy` -- deploy the contract the local hardhat node and display the resulting contract address