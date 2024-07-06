# Arbitrage between ETH and WBTC
## Introduction of arbitrage between ETH and WBTC
- This is a solidity smart contract that allows a user to get a opportunity to execute automatic arbitrage between ETH and WBTC.

&nbsp;

***

## Setup
### 1. Add `.env` file
- Based on `.env.example` , you add  `.env` file

<br>

### 2. Install modules
```
$ npm install
```

<br>

### 3. Compile & migrate contracts (on kovan testnet)
```
$ npm run migrate:kovan
```

<br>

### 4. Execute script (it's instead of testing)
```
$ npm run script:arbitrage
```

&nbsp;

***

## Remarks
- In advance (and in case of using kovan), you need to add a pair (ETH - WBTC) liquidity into uniswap pool and balancer pool.