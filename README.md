
# Konomi Token Transfer
### Konomi Token
<i>Uses Diamond Standard, EIP-2535 to create upgradable ERC20 token contract. Deployed on GOERLI testnet.</i>

### Features
- Mint Konomi Token [KNT] for free.
- Transfer Konomi token [KNT] from one wallet to another.

### Stack
- [Solidity](https://docs.soliditylang.org/en/v0.7.6/) - Object-oriented, high-level language for implementing smart contracts.
- [Ethers.js](https://web3js.readthedocs.io/en/v1.3.4/) - Allows users to interact with a local or remote ethereum node using HTTP, IPC or WebSocket.
- [Hardhat](https://hardhat.org/) - Development environment, testing framework and asset pipeline for blockchains using the Ethereum Virtual Machine (EVM).

### Open new terminal window and clone this repository
```
git clone https://github.com/aagbotemi/konomi-contract.git
```

#### Install dependencies
```
npm install
```
#### Compile smart contract
```
npx hardhat compile
```
#### Deploy smart contract 
```
npx hardhat run scripts/deploy.ts --network goerli
```

#### Hardhat help commands
```
npx hardhat help
```
