# **Cardano Governance Action Builder**

A web-based tool designed to simplify the process of creating on-chain governance actions for the Cardano blockchain. This application guides users through a step-by-step process, generating the necessary metadata and cardano-cli commands for all seven types of governance actions introduced in the Conway era.

**Live Application:** [**https://thomas-nada.github.io/GA-builder/**](https://thomas-nada.github.io/GA-builder/)

## **Features**

* **Comprehensive Builder:** Supports all seven types of governance actions: New Constitution, Hard Fork Initiation, Protocol Parameter Changes, Treasury Withdrawals, Motion of No-Confidence, Update Committee/Threshold, and the Info Action.  
* **Step-by-Step Guidance:** Breaks down the complex process of creating a governance action into simple, manageable steps.  
* **Metadata Generation:** Automatically generates the required CIP-108 compliant JSON metadata for your proposal.  
* **Command Generation:** Produces the exact cardano-cli conway commands needed to build and submit your governance action on-chain.  
* **Network Selection:** Easily toggle between Mainnet, Pre-Production, Preview, and SanchoNet to generate the correct commands for your target environment.
* **Theme Toggle:** Switch between a sleek dark mode and a clean light mode for your viewing preference.
* **In-depth Guide:** A dedicated page explaining the fundamentals of Cardano governance, the roles of different voting bodies (DReps, SPOs, CC), and best practices for writing a high-quality proposal.  
* **Complete Examples:** A library of detailed, end-to-end examples for each governance action type, from metadata to final transaction submission.  
* **User-Friendly Interface:** A clean, responsive design with clear instructions and helpful UI elements like dynamic forms and copy-to-clipboard buttons.

## **Application Pages**

The tool is divided into three main sections:

### **1\. Builder**

This is the core of the application. Here, you can:

* Select one of the seven governance action types.  
* Follow a multi-step form to input all required information.  
* Generate the metadata JSON file for your proposal.  
* Generate the cardano-cli command to create the action file on your local machine.

### **2\. Examples**

This page provides a collapsible accordion menu with a complete, multi-step example for every governance action. Each example includes:

* An example of the metadata JSON.  
* The command to create the action file.  
* The command to build the transaction.  
* The command to sign the transaction.  
* The command to submit the transaction.

### **3\. Guide**

This page is a resource for anyone new to Cardano's on-chain governance. It covers:

* What a governance action is.  
* Who votes on different actions.  
* The cost and timeline associated with proposals.  
* Best practices for writing a proposal that is clear, compelling, and likely to gain community support.

## **How to Use**

1. **Navigate to the Builder:** Select the governance action you wish to create.  
2. **Follow the Steps:** A modal window will appear, guiding you through the process.  
   * **Step 1:** Fill out the metadata for your proposal (Title, Abstract, etc.) and generate the JSON.  
   * **Step 2:** Host the generated JSON on a service like IPFS to get a URL.  
   * **Step 3:** Paste the metadata URL and fill in the remaining transaction details to generate the final cardano-cli command.  
3. **Run Commands Locally:** Copy the generated commands and run them in your own cardano-cli environment to build, sign, and submit your transaction.

## **License**

This project is licensed under the Apache License, Version 2.0.

## **Credits**

Built by [**Thomas Lindseth**](https://x.com/ThomasNordicADA) under harassment by [**Mike Hornan**](https://x.com/Hornan7).

