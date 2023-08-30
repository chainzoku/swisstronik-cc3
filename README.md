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


## Try running some of the following tasks:

```shell
npx hardhat test
npx hardhat run scripts/deploy.js
npx hardhat run scripts/mint.js --network swisstronik
```
