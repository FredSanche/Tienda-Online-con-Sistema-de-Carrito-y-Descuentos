# Online Store with Shopping Cart and Discounts System
Features
Add products to the shopping cart: Customers can add products with a name, price, and description.
View the shopping cart: Customers can see all the products they have added to their cart.
Calculate total price and apply discounts: The total price of the products in the cart is calculated, and a 10% discount is applied if the total is $100 or more.
Interactive menu: Console-based user interface to perform the mentioned actions.
Project Structure
The project consists of the following classes:

TiendaOnline: Main class that contains the interactive menu for the store.
Producto: Class representing a product in the store, with attributes for name, price, and description.
IDdescuento: Class containing the logic to apply discounts based on the total price.
Cliente: Class representing a customer, with methods to add products to the cart, show the cart, and calculate the total price with discounts.
How to Run the Project
Prerequisites: Make sure you have Java Development Kit (JDK) installed on your machine.
Clone the repository:
bash
Copiar código
git clone https://github.com/your-username/your-repository.git
Compile the project:
bash
Copiar código
javac TiendaOnline.java
Run the project:
bash
Copiar código
java TiendaOnline
Usage Example
When running the application, an interactive menu will be displayed:

vbnet
Copiar código
Menu:
1. Add products to your shopping cart.
2. View your shopping cart.
3. Make a purchase and get the total price with discounts.
4. Exit
Choose an option:
You can select an option by entering the corresponding number and following the instructions.
