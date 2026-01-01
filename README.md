# Coffee Machine Simulator (OOP) ☕️

A sophisticated system simulation that models the internal logic of a professional coffee vending machine. Built with a strictly modular **Object-Oriented** approach, it simulates resource auditing, multi-denomination currency processing, and ingredient management.

## 🚀 Simulation Features

- **Resource Inventory Auditing**: Automatically checks ingredient levels (water, milk, coffee) against drink requirements before processing orders.
- **Financial Transaction Logic**: A coin-operated payment system that validates amounts, calculates change, and tracks total profit.
- **Modular Menu System**: Standalone menu management that allows for easy expansion of drink types and pricing.
- **System Reporting**: Real-time administrative feedback on machine status and financial records.

## 🛠️ System Components

- `main.py`: The central controller that manages interaction between the machine's hardware logic and the user.
- `coffee_maker.py`: Simulates the "hardware" responsible for resource tracking and production.
- `money_machine.py`: Handles all banking, coin processing, and profit management.
- `menu.py`: Defines the drink database and provides search/retrieval functionality.
