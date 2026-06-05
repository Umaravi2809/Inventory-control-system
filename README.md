Inventory Management - Stock Management. Every shop needs to check the inventory of good it has to reorder the inventory so the inventory stays fresh and customers get continuous supply of goods.

This project is about inventory management of one vegetable and fruits shop.

Screens:
Login Screen - Only inventory manager can access the application. Ideally we want to have database with encrypted user name and password, but for simplicity purpose have embedded that in code.

Product Screen - Lists all products available at the shop. It also has data about the product like perishable days, current quantity and reorder quantity (the limit at which we need to order for fresh stock). The screen also provides option to add a new product and update / remove product (using product id).

Vendor Screen - Lists all vendors available for the shop. It also has data about the vendor like address, mail id, Active status. The screen also provides option to add a new vendor and update / remove (in case of permanently not just with Active Status change) vendor (using vendor id).

Mapping Screen - Lists all the vendor to product mapping in addition to vendor commitment for each product on price and order to delivery days. This mapping would help the inventory manager to take right decision based on need for speed and cost.

Dashboard Screen - Gives single page view for inventory manager for all products with the current inventory, reorder level, vendors available for each product with their commitment on delivery days and cost. The ones which are below the reorder level are highlighted and shown at the top. This page also accepts orders upon choosing the product, vendor and quanity in Kg.

Order Log - Gives single page view of all orders made across products

Report - Gives report on products and quantity of orders made in total for those products. This helps in identifying which product is ordered more.

There are other buttons like Clear - To clear entries and selections made and Refresh - To refresh the data table / report.

Tables: ID - Running Number, Created Date: First Insert Date, Modified Daye: Last Update Date


About the libraries used 
Python is a high-level, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation. It has a large collection of libraries and is one of the most popular languages used by computer programmers. It is also used in AI.
Pandas is a software library written for the Python programming language. Pandas is mainly used for data analysis and associated manipulation of tabular data in DataFrames. Pandas allows importing data from various file formats and databases like MySQL.
Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter.
NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions including generation of random numbers giving limits.
Tkinter is a Python binding to the Tk GUI toolkit. It is Python's de facto standard GUI. Tkinter is included with standard Linux, Microsoft Windows and macOS installs of Python.
MySQL is an open-source relational database management system (RDBMS).A relational database organizes data into one or more data tables in which data may be related to each other; these relations help structure the data.  MySQL is used with other programs to implement applications that need relational database capability.
