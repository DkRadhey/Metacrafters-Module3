# Connecting a local hardhat network with Remix
Follow the steps below to connect the Hardhat local network to Remix and work with the contract.

Step 1: Go to your project directory
Open your terminal and navigate to the project directory where your Solidity contract is located.

Step 2: Run the remixd command
Run "remixd" in the terminal to start the remixed service:

Step 3: Open Remix IDE
Open a web browser and navigate to Remix IDE.

Step 4: Connect to localhost
In the Remix IDE, click the "Connect to Localhost" button in the upper right corner. This will create a connection to your local Hardhat network.

Step 5: Create a contract
In the Remix IDE, click the "+" button in the left panel to create a new file. Enter the Solidity code for your contract or .sol file in the editor.

Step 6: Draw up the contract
In the Remix IDE, switch to the "Solidity Compiler" tab in the left panel. To compile the contract, click the "Compile" button. Make sure the compiler version matches the pragma statement in your contract.

Step 7: Deploy and interact with the contract
Switch to the "Deploy & Run Transactions" tab in the Remix IDE. From the "Environment" drop-down menu, select "Injected Web3" to connect to the Hardhat LAN.

Click on the contract name under "Deployed Contracts". You will see functions and contract variables. You can deploy the contract by clicking the "Deploy" button.

Once the contract is deployed, you can work with its functions by entering the required parameters and clicking on the appropriate function buttons.

Congratulations! You have successfully connected your local Hardhat network to Remix and deployed/interacted with the contract.

Note: Make sure your local Hardhat network is running (npx hardhat node) and that you have the necessary dependencies installed (npm install).
