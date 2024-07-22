Objective:
The primary objective of the grocery delivery application is to provide a user-friendly platform for customers to browse and purchase groceries online. The system allows users to add items to their cart, review their cart, and proceed to checkout, thereby simulating a complete online shopping experience.

Technologies Used:
Java Swing: For creating the graphical user interface (GUI) components.
Java AWT: For handling user input and action events.
CardLayout: For managing different screens (panels) within the main application window.
JFrame, JPanel, JButton, JTextArea, JScrollPane: For building the application window and its components.
GridLayout, BorderLayout: For organizing the layout of components within panels.
Features and Components:
User Interface (UI):

Main Frame: The main window of the application that holds all panels.
Panels: Separate panels for browsing items, viewing the cart, and viewing order details.
Buttons: For interacting with the application (e.g., adding items to cart, viewing cart, proceeding to checkout, and navigating back to browsing).
Backend Logic:

Groceries Map: A map to store grocery items and their prices.
Cart Map: A map to store items added to the cart and their quantities.
Action Listeners: For handling button click events and updating the cart and order details.
Working of the Application:
Browsing Items:

Users can browse through a list of grocery items displayed as buttons.
Clicking a button adds the corresponding item to the cart, updating the quantity if the item is already in the cart.
Viewing Cart:

Users can view their cart, which displays the items added, their quantities, and the total price.
A "Checkout" button allows users to proceed to the order summary.
Order Summary:

Displays the final order details, including item names, quantities, prices, and the total amount.
A "Back to Browse" button allows users to return to the browsing screen to continue shopping.
Example Code Analysis:
The provided code implements the grocery delivery application with the following key components:

Main Frame Setup:

The JFrame is initialized with a title and size.
A CardLayout is used to manage different panels (screens) within the main frame.
Three main panels are added to the card layout: BrowsePanel, CartPanel, and OrderPanel.
BrowsePanel:

Displays a list of grocery items as buttons.
Each button adds the corresponding item to the cart when clicked.
A "View Cart" button switches to the cart panel.
CartPanel:

Displays the items in the cart, their quantities, and the total price.
A "Checkout" button clears the cart and switches to the order panel, displaying the final order details.
OrderPanel:

Displays the order summary with item names, quantities, prices, and the total amount.
A "Back to Browse" button switches back to the browse panel.
Conclusion:
This grocery delivery application provides a basic but functional online shopping experience. Enhancements could include user authentication, persistent storage for the cart and orders, and a more extensive catalog of grocery items. Integration with a backend service could also be added to handle real-time data and user orders.






