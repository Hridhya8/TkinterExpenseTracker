# TkinterExpenseTracker


This guide walks through the creation of a desktop expense tracking application using Python's Tkinter for the graphical user interface (GUI) and SQLite3 for the database.

Key Steps and Components:

1. Importing Modules:
   - The necessary modules like `tkinter`, `ttk`, and `messagebox` are imported to create the GUI.

2. Creating the Main Window:
   - A Tkinter object is created, and properties like window title and size are set.

3. Global Variables:
   - Variables are defined for various inputs like item name, item price, and date of purchase using Tkinter’s `StringVar` and `IntVar`.

4. Frame and Label Widgets:
   - Frames are used to organize the layout, and labels are created to prompt users for input (e.g., Item Name, Item Price).

5. Entry Widgets:
   - Text entry fields are provided for user input.

6. Action Buttons:
   - Buttons are added to perform actions like saving records, clearing entries, exiting the app, calculating total balance, updating, and deleting records.

7. Treeview Widget:
   - A Treeview widget displays records in a tabular format, with a scrollbar for navigation.

8. Backend (Database Handling):
   - SQLite3 is used to create a database with CRUD operations encapsulated in a `Database` class.
   - The `Database` class includes methods for inserting, updating, fetching, and deleting records.

9. Functions:
   - Various functions handle operations like saving records to the database, setting the current date, and clearing entry fields.

10. Infinite Loop:
    The `mainloop()` function keeps the application running and responsive to user input.
