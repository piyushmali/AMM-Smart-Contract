# AMM Smart Contract

This repository contains an Automated Market Maker (AMM) smart contract implemented in Solidity. The contract facilitates decentralized trading by allowing users to provide liquidity in a pool of two tokens and enables token swaps between them. Liquidity providers receive Liquidity Pool (LP) tokens representing their share of the pool and can earn transaction fees.

## Key Features

- **Liquidity Provision**: Users can add liquidity to the pool by supplying two tokens.
- **Token Swaps**: The contract uses a constant product formula (x * y = k) to facilitate token swaps without relying on order books.
- **LP Tokens**: Liquidity providers receive LP tokens, representing their proportional share of the pool.
- **Fee Mechanism**: Liquidity providers earn a portion of the trading fees from swaps.
  
## How to Use

1. **Add Liquidity**: Provide equal values of two tokens to the pool and receive LP tokens in return.
2. **Swap Tokens**: Exchange between the two tokens based on the current pool reserves and swap fee.
3. **Remove Liquidity**: Redeem your LP tokens to withdraw your share of the pool, including earned fees.

## License

This project is licensed under the MIT License.
