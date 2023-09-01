# Swisstronik Code Challenges 3 (CC3)

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

## Function Implementation
dir: contracts/Token.sol [ function mint() ]
```
_mint(msg.sender,100*10**18);
```
By default the parameter is 100 Tokens.

## Information Test
```
Token Name     : ChainZoku
Symbol         : CZ
Smart Contract : 0x697965D8d1F1d9132B8c14C2Db344219461300B5
```

## Tx ID
Transfer 100 Token
```
https://explorer-evm.testnet.swisstronik.com/tx/0x56cfffa489caa634d0f55e358a2ddc21b7a3d27b8698a6369588d1230f5d370d
```

Mint 100 Token
```
https://explorer-evm.testnet.swisstronik.com/tx/0xf1e07e4d9b145274e262e3d187bef66ea99d6f01c416fdf55edf36042c0e82cb
```

## Try running some of the following tasks:

```shell
npx hardhat test
npx hardhat run scripts/deploy.js
npx hardhat run scripts/mint.js --network swisstronik
npx hardhat run scripts/transfer.js --network swisstronik
```
