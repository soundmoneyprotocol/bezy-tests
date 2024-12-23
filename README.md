# BEZY Token (BZY)

BEZY is an ERC20 token implementation built on Ethereum using OpenZeppelin contracts. It includes advanced features such as token burning, pausing, governance capabilities, and permit functionality.

## Features

- **ERC20 Standard**: Full implementation of the ERC20 standard
- **Burnable**: Tokens can be burned (destroyed) by their owners
- **Pausable**: Contract owner can pause/unpause token transfers in emergency situations
- **Permit**: Enables gasless token approvals
- **Governance**: Includes voting capabilities through ERC20Votes
- **Ownable**: Controlled access to administrative functions

## Technical Details

- **Token Name**: BEZY
- **Symbol**: BZY
- **Initial Supply**: 27,000,000,000 tokens
- **Decimals**: 18
- **Solidity Version**: ^0.8.22

## Installation

```bash
npm install
```

## Testing

Run the test suite:

```bash
npx hardhat test
```

Run with gas reporting:

```bash
REPORT_GAS=true npx hardhat test
```

## Deployment

Deploy to local network:

```bash
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.ts
```

## Security

For security concerns, please contact:
security@bezy.xyz

## License

This project is licensed under the MIT License.
