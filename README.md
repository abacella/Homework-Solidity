# Homework-Solidity

1)AssociateProfitSplitter 

It is a contract to split a specific amount equaly between 3 Accounts
When you deploy the contract you have to 
- Pick the three Account that will receive the funds and fill -one, -two and -three with its addresses.
- It is important to keep zero on the value in the first deployment
- Enter the account and the right network in the Metamask wallet
- Make sure you have funds
Once deployed you have two buttoms
1. deposit
2. balance
The First one is to transfer the money to the selected accounts
The second one is to check is there is any balance left. If everything went right the funds will be transferes

Everytime you hot the buttoms to build the contract and to deposit you will need to confirm the transaction in the Metamask wallet.

![Alt Text](/Screenshot/21.png)
![Alt Text](/Screenshot/22.png)
![Alt Text](/Screenshot/23.png)
![Alt Text](/Screenshot/24.png)

Contract deployed in the Ropsten Network 0x373acb8f8b84ac4aa99b52096a897e37d0fc1dd2
![Alt Text](/Screenshot/15.png)

2)TieredProfitSplitter

It is a contract to split a specific amount in a tiered way.
employee_one = 60%
employee_two = 25%
employee_three = 15%
When you deploy the contract you have to 
- Pick the three Account that will receive the funds and fill -one, -two and -three with its addresses.
- It is important to keep zero on the value in the first deployment
- Enter the account and the right network in the Metamask wallet
- Make sure you have funds
Once deployed you have two buttoms
1. deposit
2. balance
The First one is to transfer the money to the selected accounts
The second one is to check is there is any balance left. If everything went right the funds will be transferes

Everytime you hit the buttoms to build the contract and to deposit it you will need to confirm the transaction in the Metamask wallet.

![Alt Text](/Screenshot/12.png)
![Alt Text](/Screenshot/13.png)
![Alt Text](/Screenshot/14.png)

Contract deployed in the Ropsten Network 0x76a9a751357bb10043ba860863cbcc21c2493889
![Alt Text](/Screenshot/25.png)

3)DeferredEquityPlan

This contract gets a certain value, splits the value by 4 and alow one transfer of the splitted value per year until there is no balance
- Write the address of the account and push the distribute buttom to transfer the value for the year. If the value has already been trasnfered an error message is sent.
- There is a security buttom to stop any future transaction
- 
Contract deployed in the Ropsten Network 0xE8e02C5A99d4318451Ec5eBd1767B7aC29fbAD01
