# LastAirbender Token (Aang)

## Overview
LastAirbender (Aang) is an ERC-20 token implemented on the Ethereum blockchain. It is a basic token with burning capabilities and ownership controls. The token is named after the iconic character "Aang" from the animated series "Avatar: The Last Airbender."

## Features

### ERC-20 Standard
LastAirbender follows the ERC-20 token standard, providing compatibility with various decentralized applications (DApps), exchanges, and wallets that support this standard.

### Burning Capability
The token includes burning functionality through the integration of the `ERC20Burnable` extension. Token holders can burn their tokens, reducing the total supply.

### Ownership Control
The ownership of the contract is managed using the `Ownable` contract from OpenZeppelin. The initial owner is set during deployment, and only the owner has the authority to mint new tokens.

