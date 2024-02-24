**Overview**

**Solidity Smart Contracts for ERC20 Token and Vault**

Contained within this repository are Solidity smart contracts tailored for an ERC20 token and a vault crafted to manage deposits and withdrawals of the ERC20 token.

### Contract Description

1. **ERC20.sol**: This contract adheres to the ERC20 token standard. It offers fundamental functionalities like token transfers, authorization of spender addresses for token transfers on behalf of token owners, and token burning/minting.

2. **Vault.sol**: The vault contract acts as a secure repository for ERC20 tokens. Users can deposit tokens into the vault, which in turn will generate shares representing their ownership. These shares can subsequently be exchanged for tokens during withdrawal. The vault ensures that the total share supply accurately reflects the total deposited tokens.

### Deployment Guidelines

To deploy these contracts, adhere to the following steps:

1. Deploy ERC20.sol by specifying necessary parameters such as the token name, symbol, and initial supply.
2. Deploy Vault.sol while providing the address of the ERC20 token contract to its constructor.

### Utilization

After deployment, users can engage with the contracts in the following manner:

- **ERC20 Token**: Users can perform token transfers, authorize spender addresses, and manage token burning/minting.

- **Vault**: Users have the ability to deposit tokens into the vault, where shares are minted on their behalf. These shares can later be redeemed for tokens upon withdrawal. The vault ensures precise representation of the total deposited tokens through its share supply mechanism.

### Licensing

These contracts are licensed under the MIT License. Refer to the individual contract files for comprehensive details.

## Contact

kalpak023@gmail.com
