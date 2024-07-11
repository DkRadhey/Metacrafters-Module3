# ETH-AVAX MODULE-3

Its a smart contract to create our own ERC20 token and deploy it using HardHat or Remix. The contract owner would be able to mint tokens to a provided address and any user would be able to burn and transfer tokens.

## Description

This smart contract is written in Solidity for the Ethereum blockchain. It implements an ERC-20 token with the following features:

Minting Tokens: Upon deployment, 100 SR tokens are minted to the contract's address. 
Token Burning: Any user can burn their tokens, reducing the total supply.
This contract demonstrates the use of OpenZeppelin's ERC-20 implementation, providing a secure and standard way to create tokens. It can serve as a foundation for more complex projects.

## Getting Started

Follow the steps below to connect your local Hardhat network with Remix and interact with a contract.

### Deployment

* Step 1: Navigate to Project Directory. Open your terminal and navigate to the project directory where your Solidity contract is located.
* Run `remixd` Command
  In the terminal, run the following command to start the `remixd` service:
  ```
  cd ~/Directory/remixd
  ```
  Replace `<project_directory>` with the absolute path to your project directory. This will create a connection between Remix IDE and your local project directory.
* Step 3: Open Remix IDE
Open your web browser and go to [Remix IDE](https://remix.ethereum.org).

* Step 4: Connect with Local Host
In Remix IDE, click on the "Connect to Localhost" button in the top-right corner. This will establish a connection to your local Hardhat network.

* Step 5: Create a Contract
In Remix IDE, click on the "+" button in the left panel to create a new file. Enter the Solidity code for your contract or `.sol` file in the editor.

* Step 6: Compile the Contract
In the Remix IDE, switch to the "Solidity Compiler" tab in the left panel. Click on the "Compile" button to compile the contract. Make sure the compiler version matches the pragma statement in your contract.

* Step 7: Deploy and Interact with the Contract
Switch to the "Deploy & Run Transactions" tab in the Remix IDE. From the "Environment" dropdown, select "Injected Web3" to connect to your local Hardhat network.

Click on the contract name under the "Deployed Contracts" section. You will see the contract's functions and variables. You can deploy the contract by clicking the "Deploy" button.

## Authors

Dikshant Khurana @DkRadhey

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
