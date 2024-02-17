**Token 

### Overview
This repository contains the code for a custom ERC20 token named "degen token" (symbol: DGN). The token contract is deployed on the Ethereum blockchain and includes functionalities for token minting, burning, transferring, redeeming items, checking balances, and receiving donations. Additionally, it incorporates OpenZeppelin's libraries for ERC20, Ownable, and ERC20Burnable.

### Features
1. **Token Minting and Burning**: The contract allows the owner to mint new tokens and burn existing ones.

2. **Token Transfer**: Users can transfer tokens to other addresses.

3. **Item Redemption**: Users can redeem different models of motorcycles by burning a specific amount of tokens associated with each model.

4. **Balance Checking**: Users can check their token balance.

5. **Donation**: The contract accepts donations in Ether.

### Contract Structure
- **Token.sol**: This file contains the main contract code, including the implementation of token functionalities and event emissions.
- **OpenZeppelin Libraries**: Import statements for ERC20, Ownable, and ERC20Burnable from OpenZeppelin's contracts.

### Usage
1. **Deployment**: Deploy the contract to the Ethereum blockchain, specifying the initial token supply and the address of the initial owner.

2. **Minting**: The owner can mint additional tokens using the `mint` function, providing the recipient's address and the total number of tokens to be minted.

3. **Burning**: Tokens can be burned by calling the `burn` function, specifying the number of tokens to burn.

4. **Transfer**: Users can transfer tokens to other addresses using the `transferTokens` function.

5. **Redeem Motorcycle**: Users can redeem a motorcycle model by calling the `redeemMotorcycle` function with the desired model as an argument.

6. **Check Balance**: Users can check their token balance by calling the `checkBalance` function.

7. **Donate**: Ether donations can be made to the contract using the `receiveDonation` function.

### License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

