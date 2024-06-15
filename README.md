# AVAX-1

# Step by Step: Deploying and Testing Your EVM Subnet

This README will guide you through the process of deploying an EVM subnet using the Avalanche CLI, adding your subnet to Metamask, and deploying and testing smart contracts using Remix.

## Prerequisites

Before starting, ensure you have the following installed:

- [Avalanche CLI](https://github.com/ava-labs/avalanche-cli)
- [Metamask](https://metamask.io/) browser extension
- [Remix IDE](https://remix.ethereum.org/)

## Steps

### 1. Deploy your EVM Subnet using the Avalanche CLI

1. Open your terminal.
2. Run the following command to deploy your EVM subnet:

    ```sh
    avalanche subnet create <subnet-name>
    ```

3. Follow the prompts to configure and deploy your subnet.

### 2. Add your Subnet to Metamask

1. Open Metamask.
2. Click on the network dropdown at the top and select "Custom RPC".
3. Enter the details of your newly created subnet:
    - **Network Name:** Your subnet name
    - **New RPC URL:** The RPC URL provided during subnet creation
    - **Chain ID:** The chain ID of your subnet
    - **Currency Symbol:** (Optional) The symbol of the currency used on your subnet
    - **Block Explorer URL:** (Optional) A link to the block explorer for your subnet

4. Click "Save".

### 3. Make sure it is your selected network in Metamask

Ensure that your new subnet is selected in the Metamask network dropdown.

### 4. Connect Remix to your Metamask

1. Open [Remix IDE](https://remix.ethereum.org/).
2. Click on the "Deploy & run transactions" tab on the left sidebar.
3. Select "Injected Web3" in the "Environment" dropdown.
4. Metamask will prompt you to connect. Select your account and connect.

### 5. Use the Injected Provider

Ensure that "Injected Web3" is selected in Remix as your provider. This will connect Remix to your Metamask, allowing you to interact with your EVM subnet.

### 6. Deploy the Smart Contracts

1. In Remix, create a new file with your smart contract code.
2. Compile the smart contract using the "Solidity Compiler" tab.
3. Go to the "Deploy & run transactions" tab and deploy your contract by clicking the "Deploy" button.

### 7. Test Your Application

1. Interact with your deployed smart contracts using the Remix interface.
2. Test various functions and ensure they work as expected.
3. Deploy tokens, create pools, and perform other actions using Remix.

### Using Remix to Interact with Your Deployed Smart Contracts

You can use Remix to interact with your deployed contracts, deploy tokens, create pools, and more. Explore the functionalities provided by Remix to fully utilize your deployed smart contracts on your EVM subnet.

## Conclusion

By following these steps, you should be able to deploy your EVM subnet, add it to Metamask, connect Remix to Metamask, and deploy and test your smart contracts. If you encounter any issues, refer to the Avalanche CLI and Remix documentation for further assistance.
