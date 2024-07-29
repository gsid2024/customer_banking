# customer_banking
Homework Challenge 3 July 29
This project helps you manage and track savings and CD (Certificate of Deposit) accounts. It calculates how much money you’ll make from interest and updates your account balances.

What’s Inside
Account.py: This file has the Account class. It helps keep track of the account’s balance and interest.
savings_account.py: This has the create_savings_account function. It figures out how much interest you earn and updates the savings account balance.
cd_account.py: This file includes the create_cd_account function. It works the same way as the savings function but for CD accounts.
customer_banking.py: This is the main script. It talks to the user, gets their account details, and shows the results.


How It Works
Account.py
__init__(balance, interest): Sets up a new account with a starting balance and interest.
set_balance(balance): Updates the balance of the account.
set_interest(interest): Updates the interest earned.
savings_account.py
create_savings_account(balance, interest_rate, months):
Makes a new savings account.
Calculates interest based on how much money you have, the interest rate, and how long it’s been.
Updates the account balance with the earned interest.
Returns the new balance and interest earned.
cd_account.py
create_cd_account(balance, interest_rate, months):
Makes a new CD account.
Calculates interest just like the savings account.
Updates the balance and returns the new balance and interest earned.
customer_banking.py

How to Run It:
Just run this file: python customer_banking.py
It will ask for details about your savings and CD accounts.
Enter the balance, interest rate, and how long it’s been.
It will then show you how much interest you’ve earned and the updated balance.
