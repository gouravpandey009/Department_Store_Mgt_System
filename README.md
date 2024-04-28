# Department_Store_Mgt_System
DSMS in C++ manages store inventory and sales. Features include add, view, update, and delete items. Operations read/write data to 'book.txt'. Users modify items by item code, and delete items by code. Control panel offers options; program exits on 'Exit'.

The Department Store Management System (DSMS) in C++ streamlines inventory and sales management via a command-line interface. It facilitates admin tasks like add, view, update, and delete operations.

Add Functionality:
Prompt users for item details (Item Code, Name, Company, Quantity).
Option to add another item (y/n) after each entry.

View Functionality:
Displays information for all store items.

Update Functionality:
Users input item code to identify the product.
Modify details such as Item Code, Name, Company, and Quantity.

Delete Functionality:
Users enter item code to delete the item.
Displays error message for invalid commands.

Approach:
Utilizes a "dept" class containing main functions for operations.
Control panel function displays available options.
Functions created for add, view, update, and delete tasks.
Data operations read/write to 'book.txt' file.
Update function checks and modifies item details in the file.
Delete function locates and removes items from the file.
Program exits upon selecting the Exit option.

Overall, the DSMS efficiently manages store inventory and sales, offering a user-friendly experience for administrators.
