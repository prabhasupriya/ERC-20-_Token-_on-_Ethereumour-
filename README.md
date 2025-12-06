# MyToken (MTK)

## Overview
MyToken is a simple ERC-20 compatible token built on Ethereum for learning purposes.

## Token Details
- **Name**: MyToken  
- **Symbol**: MTK  
- **Decimals**: 18  
- **Total Supply**: 1,000,000 MTK  

## Features
- ✅ Standard ERC-20 implementation  
- ✅ Transfer tokens between addresses  
- ✅ Approve and transferFrom functionality  
- ✅ Event emission for transparency  
- ✅ Balance tracking  

## How to Deploy
1. Open **Remix IDE**
2. Create new file: `MyToken.sol`
3. Paste the contract code
4. Compile using **Solidity 0.8.x**
5. Go to **Deploy & Run Transactions**
6. Enter constructor value:

```
1000000000000000000000000
```

7. Click **Deploy**

## How to Use

### Check Balance
```solidity
balanceOf(address account) → returns uint256
```

### Transfer Tokens
```solidity
transfer(address to, uint256 amount) → bool
```

Example:
```
transfer(0xReceiverAddress, 1000000000000000000)
```
(Sends **1 MTK**)

### Approve Spending
```solidity
approve(address spender, uint256 amount) → bool
```

Example:
```
approve(0xSpenderAddress, 2000000000000000000)
```
(Approves **2 MTK**)

### Delegated Transfer
```solidity
transferFrom(address from, address to, uint256 amount) → bool
```

Example:
```
transferFrom(0xOwnerAddress, 0xReceiverAddress, 1000000000000000000)
```
(Spender transfers **1 MTK**)

### Check Allowance
```solidity
allowance(address owner, address spender) → uint256
```

## Screenshots
Include screenshots of:
- ✅ Successful compilation  
- ✅ Contract deployment  
- ✅ Token details (name, symbol, decimals, supply)  
- ✅ Transfer transactions  
- ✅ Approval & transferFrom  
- ✅ Transfer and Approval events
