NAME:MANCHIKANTI JAHNAVI
COMPANY:CODETECH IT SOLUTIONS
ID:CT08DS565                                                                                                                                                                               DOMAIN:PYTHON PROGRAMMING
DURATION:JULY 23RD TO AUGUST 23RD 2024


Library Management System
Overview:
This Python program provides a basic library management system that allows users to manage library resources such as books, magazines, and DVDs. The system supports adding new items to the library, checking out and returning items, managing overdue fines, and searching for items by various criteria.
 ![Uploading WhatsApp Image 2024-07-25 at 5.47.35 PM.jpeg…]()

Features:
Add Items: Users can add new items to the library. Each item has a title, author, category, and type (e.g., book, magazine, DVD).

Check Out Items: Users can check out items from the library. Checked-out items are assigned a due date (14 days from the current date), and their status is updated accordingly.

Return Items: Users can return items to the library. The system calculates overdue fines based on the number of days past the due date. If an item is returned late, the overdue fine is displayed.

Search Items: Users can search for items by title, author, or category. The search function returns a list of matching items.

Display All Items: Users can view all items currently in the library, including their status and due date.

Classes and Methods:
LibraryItem Class:

Represents a library item with attributes: title, author, category, item_type, status, and due_date.
Provides a string representation of the item for easy display.
Library Class:

Manages a collection of LibraryItem objects.
Methods include:
add_item(title, author, category, item_type): Adds a new item to the library.
check_out(title): Checks out an item, setting its status to "checked out" and assigning a due date.
return_item(title): Returns an item, calculates overdue fines if applicable, and updates its status.
search(query): Searches for items by title, author, or category.
display_all_items(): Displays all items in the library.
main Function:

Provides a command-line interface for interacting with the library system.
Users can choose options to add items, check out or return items, search for items, display all items, or exit the program.
Example Usage:
Add Items: Add a book titled "Python Programming" with the author "John Doe" to the library.
Check Out Items: Check out the "Python Programming" book. The book will have a due date of 14 days from today.
Return Items: Return the "Python Programming" book. If it's overdue, the system will display a fine.
Search Items: Search for items containing the query "Python" in their title or author.
Display All Items: View all items in the library, including their current status and due date.
