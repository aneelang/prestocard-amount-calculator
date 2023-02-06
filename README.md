## Getting started.

After you've cloned this program 
  - Add your current balance to the 'balance' variable and the number of hours you want to travel to 'number_of_hours_user_adds' variable and run the program to get the correct amount you need to add to get a perfect 0 after your trips.

NOTE: If you'd like to be safe, always add another 1 - 2 dollars for your safety, but the output from program will return an amount which is the exact required for your to travel the number of hours in MiWay.


# Method used to develop

This is a simple mathematical series question.

Let **x** be the number of hours a user wants to travle in MiWay.
Let **balance** be the current balance and **amount_to_add** be the amount to be added for going for those trips, then the equation is

**amount_to_add = ((3.10 - balance > 0 )? (3.10 - balance) : 0) + (3.10 * x // 2)**

This will give us the exact value needed.
