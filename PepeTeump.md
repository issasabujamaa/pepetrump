# Solidity API

## ERC20Interface

### Contract
ERC20Interface : scripts/PepeTeump.sol

 --- 
### Functions:
### totalSupply

```solidity
function totalSupply() public view returns (uint256)
```

### balanceOf

```solidity
function balanceOf(address tokenOwner) public view returns (uint256 balance)
```

### allowance

```solidity
function allowance(address tokenOwner, address spender) public view returns (uint256 remaining)
```

### transfer

```solidity
function transfer(address to, uint256 tokens) public returns (bool success)
```

### approve

```solidity
function approve(address spender, uint256 tokens) public returns (bool success)
```

### transferFrom

```solidity
function transferFrom(address from, address to, uint256 tokens) public returns (bool success)
```

 --- 
### Events:
### Transfer

```solidity
event Transfer(address from, address to, uint256 tokens)
```

### Approval

```solidity
event Approval(address tokenOwner, address spender, uint256 tokens)
```

## SafeMath

### Contract
SafeMath : scripts/PepeTeump.sol

 --- 
### Functions:
### safeAdd

```solidity
function safeAdd(uint256 a, uint256 b) public pure returns (uint256 c)
```

### safeSub

```solidity
function safeSub(uint256 a, uint256 b) public pure returns (uint256 c)
```

### safeMul

```solidity
function safeMul(uint256 a, uint256 b) public pure returns (uint256 c)
```

### safeDiv

```solidity
function safeDiv(uint256 a, uint256 b) public pure returns (uint256 c)
```

## PepeTrump

### Contract
PepeTrump : scripts/PepeTeump.sol

 --- 
### Functions:
### constructor

```solidity
constructor() public
```

Constrctor function

     * Initializes contract with initial supply tokens to the creator of the contract

### totalSupply

```solidity
function totalSupply() public view returns (uint256)
```

### balanceOf

```solidity
function balanceOf(address tokenOwner) public view returns (uint256 balance)
```

### allowance

```solidity
function allowance(address tokenOwner, address spender) public view returns (uint256 remaining)
```

### approve

```solidity
function approve(address spender, uint256 tokens) public returns (bool success)
```

### transfer

```solidity
function transfer(address to, uint256 tokens) public returns (bool success)
```

### transferFrom

```solidity
function transferFrom(address from, address to, uint256 tokens) public returns (bool success)
```

inherits SafeMath:
### safeAdd

```solidity
function safeAdd(uint256 a, uint256 b) public pure returns (uint256 c)
```

### safeSub

```solidity
function safeSub(uint256 a, uint256 b) public pure returns (uint256 c)
```

### safeMul

```solidity
function safeMul(uint256 a, uint256 b) public pure returns (uint256 c)
```

### safeDiv

```solidity
function safeDiv(uint256 a, uint256 b) public pure returns (uint256 c)
```

inherits ERC20Interface:
### totalSupply

```solidity
function totalSupply() public view returns (uint256)
```

### balanceOf

```solidity
function balanceOf(address tokenOwner) public view returns (uint256 balance)
```

### allowance

```solidity
function allowance(address tokenOwner, address spender) public view returns (uint256 remaining)
```

### transfer

```solidity
function transfer(address to, uint256 tokens) public returns (bool success)
```

### approve

```solidity
function approve(address spender, uint256 tokens) public returns (bool success)
```

### transferFrom

```solidity
function transferFrom(address from, address to, uint256 tokens) public returns (bool success)
```

 --- 
### Events:
inherits SafeMath:
inherits ERC20Interface:
### Transfer

```solidity
event Transfer(address from, address to, uint256 tokens)
```

### Approval

```solidity
event Approval(address tokenOwner, address spender, uint256 tokens)
```

