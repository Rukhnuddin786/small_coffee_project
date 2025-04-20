☕ Coffee Machine Simulator

This Python script simulates a basic coffee machine that serves three types of drinks: espresso, latte, and cappuccino. It keeps track of the ingredients, handles user input for ordering drinks, checks if resources are sufficient, processes coin transactions, and updates the available resources and profit.

🔧 Features
Offers 3 drink choices: espresso, latte, and cappuccino

Checks if there are enough ingredients for the selected drink

Accepts coin input (quarters, dimes, nickels, pennies) and calculates total payment

Handles transaction logic and returns change if necessary

Deducts used ingredients from the machine’s resources

Maintains and displays a profit report

Allows shutting down the machine with the command off

Displays current resources and earnings with the command report

🧠 How it works
User Input: The program repeatedly prompts the user to choose a drink or type report or off.

Resource Check: It checks if there are enough resources to make the selected drink.

Coin Input: If resources are sufficient, the user is prompted to insert coins.

Transaction Handling: If enough money is inserted, the drink is served, and change is given if applicable.

Update Resources: Used ingredients are subtracted from the available resources.

📌 Example Commands
espresso: Orders an espresso

latte: Orders a latte

cappuccino: Orders a cappuccino

report: Displays the current status of water, milk, coffee, and money

off: Shuts down the coffee machine

💡 Notes
The coin values are calculated using U.S. denominations.

The initial resource values are:

Water: 300ml

Milk: 200ml

Coffee: 100g

The machine profit starts at $0.
