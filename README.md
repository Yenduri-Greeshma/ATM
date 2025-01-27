# Overview
This Python program simulates an ATM interface. It allows a user to perform basic banking operations, including logging in with a PIN, crediting, and debiting money from their account. Here's how it works step-by-step:

Welcome Message:
The program begins by displaying a welcome message and asks the user how they are doing.

PIN Verification:
A predefined PIN (18032004) is set.
The user is prompted to enter the PIN.
If the entered PIN matches the predefined PIN, the program proceeds to the banking operations.
If the PIN is incorrect, the user is prompted to re-enter it.
Banking Operations: After successful login, the program offers two options:

Credit:
The user enters the amount they want to add to their account.
The program calculates and displays the new total balance (balance + add).
It then displays a thank-you message.

Debit:
The user enters the amount they want to withdraw.
If the withdrawal amount is less than the current balance, the program deducts the amount and shows the remaining balance.
If the withdrawal amount exceeds the balance, it displays an "Insufficient Balance" message.

Exit:
The program terminates after a successful transaction (credit or debit) or when the user chooses to exit.


Key Features:-
1. PIN Security: Ensures that only users with the correct PIN can access the account.
2. Error Handling for Debit: Prevents overdraw by checking the withdrawal amount against the account balance.
3. User-Friendly Messages: Includes polite prompts and a thank-you message after completing a transaction.
4. Emoji Integration: Adds a smiley emoji (\U0001F600) to enhance user interaction.

Code Link:-
https://github.com/Yenduri-Greeshma/ATM/blob/main/ATM.py
