# Day - 15
Develop a type system to describe how to work with a Bank account.
The status of the account is determined by its number, data about the account owner (name,
last name), the amount on the account and some bonus points that
increase/decrease each time you Deposit/write off the account to
different values for Deposit and withdrawals and calculated according to the
some values of the "cost" of the balance and the "cost" of replenishment.
The values of the" cost "of the balance and the" cost " of replenishment are integer
values and depend on the account type, which can be, for example, Base, Gold,
Platinum.
To work with the account, implement the following features:
- make a Deposit to your account;
- make a write-off from the account;
- create a new account;
- close an account.
You can use fake implementation to store account information
repository (storage) as a wrapper class for The list&lt;Account&gt; collection.
The work of classes to demonstrate the example of a console application.
Consider the following options when designing types
expansion/functionality changes
- adding new account types;
- edit/add sources store information about accounts;
- change the logic of calculating bonus points;
- change the logic of account number generation.
