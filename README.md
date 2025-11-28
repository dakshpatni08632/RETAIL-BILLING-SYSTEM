Project Title - Retail Billing System 

Overview of the Project
This is a small project I created for my CSE1021 course, Introduction to Problem Solving and Programming. This is essentially an extremely basic, text-based checkout system, also written in its entirety in Python. This basically emulates a small store counter: you select items, the program calculates the cost, and then you pay.

What It Can Do (Features)
• Fixed Menu: I have set a small inventory of products and their prices, in a helpful Python dictionary.
• Easy Shopping: You can keep adding as many items as you want to your virtual cart.
• Instant Billing: It calculates the sub-total for everything automatically and provides you with a final Grand Total.
• Simple Checkout: It emulates a payment, which requires you to enter the exact amount requested to make a sale.
•Straightforward Prompts: Everything is regulated through simple number inputs in the console menu.

Technologies/Tools Used
1.	The language used here is python 3.x and it is Core language  and used throughout the application.
2.	The product list made here using python dictionaries these Dictionaries are ideal for finding prices instantly, using the name of the item as a key.
3.	The Shopping cart made here using Python List (cart_list) here Lists are ideal for the addition of items dynamically as the user shops.
4.	The Flow Control are made using while loops & if/else.This is Essential for keeping the application running and managing decisions.


STEPS TO INSTALL AND RUN
1. Confirm the same version of Python as used in the project.
2. Open your terminal or command prompt.
3. Navigate to the directory where you want the project to reside.
4. Use the command: 
5.Running Python code often requires a controlled environment to ensure compatibility. Use tools like virtualenv or conda to isolate the project dependencies.
6. Navigate to the directory containing the Python script you want to run.

Instructions for Testing
•  Initial Input: 1
•	Expected Output: Displays the full list of 10 items and their prices.
•	Status: SUCCESS
•  Add Items: 'MILK' (Qty 2), 'BREAD' (Qty 1), then 'DONE'
•	Expected Output:
o	Cart: [('MILK', 2), ('BREAD', 1)]
o	Grand Total: 80*2 + 40*1 = 200
•	Status: SUCCESS
•  Add Invalid Item: 'TEA LEAVES' (Qty 1), then another invalid item
•	Expected Output: Prints "INVALID INPUT, TRY AGAIN", continues the input loop.
•	Status: SUCCESS
•  Payment: Enter amount equal to Grand Total
•	Expected Output: Prints "PAYMENT SUCCESSFUL, THANK YOU"
•	Status: SUCCESS
•  Payment: Enter amount NOT equal to Grand Total
•	Expected Output: Prints "TRY AGAIN...", loops until correct payment is entered.
•	Status: SUCCESS


My Takeaways
This project really hammered home the importance of:
1.	Knowing when to use a Dictionary vs. a List.
2.	Mastering while loops for continuous user interaction handling.
3.	Input Handling reality- much more difficult than I thought to ensure that users give you the input you expect!






