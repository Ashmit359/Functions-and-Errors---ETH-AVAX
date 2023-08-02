Functions-and-Errors---ETH-AVAX-Smart-Contract-
A smart contract that implements the require(), assert() and revert() statements.

Smart Contract Error Handling
This repository contains a Solidity smart contract that demonstrates the usage of assert, revert, and require statements for error handling. The contract includes functions for depositing and withdrawing funds, as well as checking the contract's balance.

Usage
To interact with the smart contract, you can use Remix, an online Solidity IDE. Follow these steps:

Go to the Remix website.

Create a new file and save it with a .sol extension (e.g., FunctionsAndErrors.sol).

Copy and paste the provided Solidity code into the file.

Click on the "Solidity Compiler" tab and set the compiler version to 0.8.18 (or another compatible version). Click on "Compile FunctionsAndErrors.sol" to compile the code.

Deploy the contract by clicking on the "Deploy & Run Transactions" tab. Select the "FunctionsAndErrors" contract from the dropdown menu and click "Deploy."

Once the contract is deployed, you can interact with it using the provided functions:

Use the deposit function to deposit funds into the contract.
Use the withdraw function to withdraw a specified amount from the contract.
Use the checkBalance function to view the contract's current balance.
Error Handling
The contract uses require statements for regular error handling, such as checking for valid conditions before proceeding with transactions. If a require statement evaluates to false, the transaction is reverted, and any gas consumed until that point is refunded to the caller.

The assert statement is used for internal checks that should never be false under any circumstances. If an assert statement evaluates to false, it indicates a critical error, and the transaction will be reverted, consuming all remaining gas and discarding all state changes made up to that point.

The revert statement is used for regular error handling and allows you to provide custom error messages. When executed, it reverts the transaction with a custom error message.

Please use this contract as a reference to understand error handling in Solidity and how to use these statements effectively in your smart contracts. Feel free to explore and modify the code to suit your needs.

Author :
Ashmit kumar sinha
