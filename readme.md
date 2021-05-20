# Banking Kata

## Kata goal
Improve TDD skills

## Requirements

### Iteration 1:
Write a class Account that offers the following methods void deposit(int) void withdraw(int) String printBalance() 
Balance can not be negative.
If a withdraw is made and money is insuficcient, the balance won't be modified, and no messages will be shown.

An example of Balance would be:

    Balance: 500
    
 ### Iteration 2
 Add to class Account a method that shows an historical of movements: List<String> printMovements()
 Every element from the list that is returned, is a new line.
 If a withdraw is made and money is insuficcient, the movement won't be stored

  
  An example of Movements would be:
 
  ```
Movements 
-250 50
+300 300
 ```
