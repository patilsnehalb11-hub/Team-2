Canteen Food Ordering System

Project Overview

The Canteen Food Ordering System is a simple software project used to manage food ordering in a canteen. It allows customers to enter their details, view available menu items, select food items, check item availability, and calculate the total bill.

Objectives

- To make the food ordering process simple and easy.
- To display available food items.
- To store customer and order details.
- To check food item availability.
- To calculate the total bill automatically.
- To reduce manual work in the canteen.

Requirements

1. Functional Requirements

- Enter customer details.
- Display menu items.
- Select food items.
- Check item availability.
- Add available items to the order.
- Calculate the total bill.
- Display order details and bill.

2. Non-Functional Requirements

- Easy to use.
- Simple and user-friendly interface.
- Fast response.
- Accurate bill calculation.
- Reliable system.
- Easy to maintain.

3. User Requirements

- Customer should be able to enter personal details.
- Customer should be able to view the menu.
- Customer should be able to select food items.
- Customer should be able to know item availability.
- Customer should be able to view the final bill.

4. System Requirements

- Computer or laptop.
- Operating system: Windows/Linux.
- Required programming environment.
- Database system, if used.
- Basic input and output devices.

Features

Customer Details

Stores customer information such as Customer ID, Name, and Phone Number.

Menu Items

Displays food item name, price, and availability.

Order Details

Stores order information such as Order ID, Customer ID, order date, and total amount.

Item Availability

Checks whether the selected food item is available or not.

Bill Calculation

Calculates the total amount based on selected food items and quantities.

Algorithm

1. Start.
2. Enter customer details.
3. Display menu items.
4. Select a food item.
5. Check item availability.
6. If the item is available, add it to the order.
7. If the item is unavailable, display "Item Not Available".
8. Ask whether the customer wants to order another item.
9. If yes, select another food item.
10. Calculate the total bill.
11. Display order details and bill.
12. End.

ER Diagram

Entities

CUSTOMER

- Customer_ID
- Name
- Phone

MENU_ITEM

- Item_ID
- Item_Name
- Price
- Availability

ORDER

- Order_ID
- Customer_ID
- Order_Date
- Total_Amount

ORDER_ITEM

- Order_Item_ID
- Order_ID
- Item_ID
- Quantity
- Sub_Total

BILL

- Bill_ID
- Order_ID
- Total_Amount
- Bill_Date

Flowchart

The flowchart represents the complete food ordering process:

Start → Enter Customer Details → Display Menu Items → Select Food Item → Check Availability → Add Item to Order → Ask for Another Item → Calculate Total Bill → Display Order Details and Bill → End

If the item is not available, the system displays "Item Not Available" and asks the customer to select another item.

Project Structure

Canteen-Food-Ordering-System/
│
├── README.md
├── Requirements
├── Algorithm
├── Flowchart
├── ER-Diagram
└── Project Files

Advantages

- Saves time.
- Reduces manual work.
- Easy food ordering.
- Accurate bill calculation.
- Easy to manage customer and order details.
- Helps to check food availability.

Conclusion

The Canteen Food Ordering System provides a simple and efficient way to manage food orders in a canteen. It helps customers select food items, checks availability, manages order details, and calculates the final bill easily. Team-2
