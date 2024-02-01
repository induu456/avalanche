# Solidity

This is a basic implementation of an ERC-20 token named "Solidity by Example" (SOLBYEX) using the Ethereum blockchain.

## Contract Details

- **Name**: Solidity by Example
- **Symbol**: SOLBYEX
- **Decimals**: 18
- **Total Supply**: [initial supply, set during contract deployment]

## Functions

### `transfer`

```solidity
function transfer(address recipient, uint amount) external returns (bool)
function approve(address spender, uint amount) external returns (bool)
function transferFrom(address sender, address recipient, uint amount) external returns (bool)
function mint(uint amount) external
