# Hello World
This solidity program is a creation of an example token. The purpose of this program is to become a reference for the future programmers that are finding something to start on. 

## Description

This program is a simple token where it includes the public variables that store the details about the coin, mapping of addresses to balances, a mint function that increases your balances with your input amount, and a burn function the decreases your balances with your input amount.
## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the example code from the file MyToken (MyToken)

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile MyToken.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by scrolling down to the "Deployed/Unpinned Contract" then click the arrow icon. From there, you can copy the address that is located above the "gas limits" and below the "environment" when you scroll up. 

Then you'll scroll down again and paste the copied address to the "_address" typebox. After that, You can add any value you want. Paste the address again on the typebox beside the "balance" to see if the balance is the same as your input. 

Burn and Mint function has the same instruction to work, it's just that Mint function will add the value to the balance and Burn function will decrease the value in your balance.

## Authors
Diane Princess A. Barce



## License

This project is licensed under the MIT License - see the LICENSE.md file for details
