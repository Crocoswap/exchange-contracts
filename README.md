# Croco Smart Contracts
This repo contains all of the smart contracts used to run [Crocoswap](crocoswap.org).

## Deployed Contracts
Factory address: `https://ftmscan.com/address/0x01fd54b82669a8e14310dda303e3f172afa5a585`

Router address: `0x3F778C568Efb479a1dF4AD61c54c83ECB34eB4C8`

## Running
These contracts are compiled and deployed using [Hardhat](https://hardhat.org/). They can also be run using the Remix IDE. A tutorial for using Remix is located [here](https://docs.avax.network/build/tutorials/platform/deploy-a-smart-contract-on-avalanche-using-remix-and-metamask).

To prepare the dev environment, run `yarn install`. To compile the contracts, run `yarn compile`. Yarn is available to install [here](https://classic.yarnpkg.com/en/docs/install/#debian-stable) if you need it.

## Accessing the ABI
If you need to use any of the contract ABIs, you can install this repo as an npm package with `npm install --dev @crocoswap/exchange-contracts`. Then import the ABI like so: `import { abi as ICrocoPairABI } from '@crocoswap/exchange-contracts/artifacts/contracts/croco-core/interfaces/ICrocoPair.sol/ICrocoPair.json'`.

## Attribution
These contracts were adapted from these Uniswap repos: [uniswap-v2-core](https://github.com/Uniswap/uniswap-v2-core), [uniswap-v2-periphery](https://github.com/Uniswap/uniswap-v2-core), and [uniswap-lib](https://github.com/Uniswap/uniswap-lib).
