Coffee Machine (OOP) ☕️

This project is a sophisticated coffee machine simulation that demonstrates the power of Object-Oriented Programming (OOP) in Python. Instead of a single script, the system is divided into multiple specialized classes that interact to manage resources, process payments, and serve drinks.

🚀 Key Features

Modular Architecture: The system is split into four distinct modules: Menu, CoffeeMaker, MoneyMachine, and the main controller.

Resource Management: Tracks inventory of water, milk, and coffee, preventing orders if ingredients are insufficient.

Payment Processing: Handles multiple coin denominations (quarters, dimes, nickels, pennies) and calculates change accurately.

Dynamic Menu: A standalone menu class that manages different drink types and their associated costs/ingredients.

🛠️ Project Structure

main.py: The central logic that orchestrates the interaction between the classes and handles user input.

coffee_maker.py: Manages the physical resources and the coffee-making process.

money_machine.py: Handles all financial transactions, profit tracking, and coin validation.

menu.py: Defines the available drinks and provides search functionality.

🎮 How to Use

Check Status: Type report to see current resource levels and total profit.

Order: Type the name of the drink (e.g., latte).

Payment: Insert coins as prompted; the machine will calculate change or refund if the amount is insufficient.

Maintenance: Type off to shut down the machine.
