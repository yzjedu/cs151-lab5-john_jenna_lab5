Lab 5 algorithm 
Set balance to 1,000. 
Set choice (or option) to an empty string.
Set SENTINEL to 'E'.
While choice is not equal to SENTINEL:
1. Ask the user to choose: Deposit, Withdraw, View Balance, or Exit (display options). 
2. Based on the user's choice: 
3. Deposit:
   a.Prompt the user to enter a deposit amount. 
   b. If the amount is positive, add it to balance and display the new balance and the deposit amount. 
   c. If the amount is negative, display an error message ("Deposit amount must be positive").
4. Withdraw: 
 a. Prompt the user to enter a withdrawal amount. 
 b. If the amount is positive, subtract it from balance and display the new balance and the withdrawal amount. 
 c.If the amount is negative, display an error message ("Withdrawal amount must be positive").
 d. If the balance becomes negative, display a message warning about a potential interest rate of 55%. 
   5. View Balance: 
       a. Display the current balance. 
   6. Exit:
    a. If the user selects 'E', exit the loop and display a farewell message.
    b. If the user enters an invalid choice, display an error message ("Invalid choice, please select a valid option").
The program should continue looping until the user selects 'E' to exit.
