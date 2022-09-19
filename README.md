# Cybergame_Cafe_Management_System
A simple python administration system to help run a cybergame cafe.

DESCRIPTION:
===========
This program (CCMS) will be installed on all computers of an Cybergame Cafe business. To use the computer, the user must log in with 2 types of account: user_account for guests and admin_account for admin.

REQUIREMENTS:
===========
* user_account:
  - Have a money_count. Unable to log in if money_count = 0.
  - Have a timer that countdown to 0. The more money the account have, the more time it have on the timer. As it count_down, deplete money_count. Automatically logout if timer (money_count) reach 0.
  - Can spend money in money_count to order food from menu.
  
* admin_account:
  - Have a list of all user_accounts
  - Can create/delete user_accounts
  - Can increase money_count of user_accounts
  - Receive food orders from user_accounts. 
  - Log all transactions.
