# Onchain SVG Nfts with ChainLink Price Feed 

This project allows to host images and metadatas directly onChain.

There is two differents designs for the NFTs, when you mint, decide a price. If the current price of ETH is equal or superior to this price, you will have a happy NFT, otherwise, you will have a sad NFT.

## Launch Local Blockchain

```
yarn hardhat node --no-deploy
```

## Deploy on Local Blockchain

```
yarn hardhat deploy
```

## Deploy on Goerli

```
yarn hardhat deploy --network goerli
```

## Test on Local Blockchain

The interface 'contracts/test/VRFCoordinatorV2Mock.sol' allows to test the VRF on the local Blockchain

```
yarn hardhat test
```