# joint-savings-solidity
### A Solidity smart contract that creates a joint savings account.

---
## Technologies
* Solidity 0.5.0
* remix.ethereum.org

---
## Summary
This joint-savings Solidity contract implements setter functions:
* setAccounts: define two account addresses
* deposit: Add funds to contract
* withdraw: Send funds to one of the defined account addresses
 
And getter functions:
* contractBalance: Display contract balance
* lastToWithdraw: Show which account last withdrew funds
* lastWithdraw: Show last amount withdrawn

---
## Screenshots

Set up two account addresses:
![Set accounts](Execution_Results/set_accounts.jpg)

Add 1 ETH in wei to contract:
![Add 1 ETH in wei](Execution_Results/add_1e18_wei.jpg)

Add 10 ETH in wei to contract:
![Add 10 ETH in wei](Execution_Results/add_10e18_wei.jpg)

Add 5 ETH to contract:
![Add 5 ETH](Execution_Results/add_5_ETH.jpg)

Withdraw to account1:
![Withdraw to account1](Execution_Results/5_ETH_to_account1.jpg)

Withdraw to account2:
![Withdraw to account2](Execution_Results/10_ETH_to_account2.jpg)


---
## Contributors

[David Jonathan](https://www.linkedin.com/in/david-jonathan-1b9470/)

---
## License

Licensed under the [MIT License](https://github.com/tmbo/questionary/blob/master/LICENSE). Copyright 2022 David Jonathan