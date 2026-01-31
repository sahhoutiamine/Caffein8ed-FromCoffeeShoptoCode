=== COFFEE SHOP SYSTEM - ANALYSIS DOCUMENT ===
Team Members: [Amine SAHHOUTI, Khadija ABIRAT]
Date: [01/31/2026]

1. PROBLEM STATEMENT (in our own words):
   1. dynamic menu to Track beverages (name, type, price)
   2. system to record the customers orders to simplify the order calculation (1 order = 1 customer + multiple beverages)
   3. history that saves daily commands

2. IDENTIFIED ACTORS:

- Client : view the menu
- Waiter : create order , cancel order, create transaction
- Aowner : view daily transactions, manage menu

3. CORE CLASSES (with key properties):
   Abstract class: User (id, name, email)
   class: Waiter extends User
   class: Aower extends User
   class: Order (id, order_date, status)
   class: Deverage (id, name, type, price)
   class: Order_Beverages (id, order_id, id_drink, quantity)
   class: Transaction (id, , transaction_date, order_id, total_price)

4. KEY METHODS NEEDED:

- [Method name]: [What it does and what class it belongs to]
- Example: "Order->calculateTotal(): returns the sum of all beverage prices"

5. CRITICAL DISCOVERIES:

- What was your "aha!" moment?
- What tricky problem did you solve?
