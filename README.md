# Challenge 20 - Joint Savings Account

For this Challenge, the program "joint_savings.sol" will be written to set up an joint account.  The program was designed to run as a Solidity contract, a software language that is used to write Smart Contracts that will run on the Ethereum Blockchain.  The program was written and debugged in a web site called Remix (remix.ethereum.org).  The following steps were taken:

    A. Write and debug the joint_account.sol

    B. Once debugged, the program was compiled with the compiler set to accept a Pragma 0.5.0 as is found in the first line of code in the joint_account.sol program

    C. The Remix IDE environment was set to Remix VM (London).  This was formerly called JavaScript VM

    D. After the program was successfully compiled and the Environment set as described in C. above, the program was then Deployed.  

![Deployed](https://github.com/Cryptopher2022/Challenge_20/blob/main/Execution_Results/Successful_Deploy.png)

## Tasks to be completed

Once the steps above were accomplished, the following tasks were taken and screenshots were captured:

    A. Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.

        NOTE
        You can either use the following Ethereum addresses or create new, dummy addresses on the Vanity-ETH (Links to an external site.) website, which includes an Ethereum vanity address generator.

    Dummy account1 address:
    
    0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb
    
    Dummy account2 address: 
    
    0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0

    B. Test the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, use the contractBalance function to verify that the funds were added to your contract:

        i. Transaction 1: Send 1 ether as wei.

        ii. Transaction 2: Send 10 ether as wei.

        iii. Transaction 3: Send 5 ether.

    NOTE
    Remembering how to convert ether to wei and vice versa can be challenging. So, you can use a website like Ethereum Unit Converter (Links to an external site.) to ease doing the conversion.

    Once you’ve successfully deposited funds into your contract, test the contract’s withdrawal functionality by withdrawing 5 ether into accountOne and 10 ether into accountTwo. After each transaction, use the contractBalance function to verify that the funds were withdrawn from your contract. Also, use the lastToWithdraw and lastWithdrawAmount functions to verify that the address and amount were correct.

All of these tasks are found below and in the Execution_Results folder in the Challenge 20 repository.

## 1. Set Accounts
![Set_Accounts](https://github.com/Cryptopher2022/Challenge_20/blob/main/Execution_Results/Set_accounts.png)

## 2. Transaction 1 - Send 1 Ether (ETH) as wei
![Add_1ETH_as_wei](https://github.com/Cryptopher2022/Challenge_20/blob/main/Execution_Results/Add_1ETH_as_wei.png)

## 3. Transaction 2 - Send 10 ETH as wei
![Add_10ETH_as_wei](https://github.com/Cryptopher2022/Challenge_20/blob/main/Execution_Results/Add_10ETH_as_wei.png)

## 4. Transaction 3 - Send 5 ETH
![Send_5ETH](https://github.com/Cryptopher2022/Challenge_20/blob/main/Execution_Results/Send_5ETH.png)

## 5. Withdraw 5 ETH to Account One (utilizing the ContractBalance function, LastToWithdraw function and LastWithdrawAmount function to verify the successful transaction )
![Withdraw_5ETH_to_Account_One](https://github.com/Cryptopher2022/Challenge_20/blob/main/Execution_Results/Withdraw_5ETH_to_account1.png)

## 6. Withdraw 10 ETH to Account Two (utilizing the ContractBalance function, LastToWithdraw function and LastWithdrawAmount function to verify the successful transaction )
![Withdraw_10ETH_to_Account_Two](https://github.com/Cryptopher2022/Challenge_20/blob/main/Execution_Results/Withdraw_10ETH_to_account2.png)


    
---

## Technologies

This project was written in Solidity (https://www.solidity.io/).  The test environment was completed in Remix (as cited above).  


---

## Installation Guide

The author wrote and debugged joint_account.sol in Remix.  The program was then compiled and deployed and all of the screenshots found below (and in the Execution_Results folder in the repository).  Each task outlined above were then accomplished in Remix.  
---


## Contributors

This program was written and debugged by Christopher Todd Garner
---

## License

Feel free to use this program with appropriate references where large code blocks are copied verbatim.  
