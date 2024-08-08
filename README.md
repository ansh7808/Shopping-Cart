# Shopping-Cart
The shopping cart web application is a user-friendly, interactive platform developed using React.js and Redux, designed to simulate a real-world e-commerce shopping experience. This application allows users to select items, add them to their cart, remove items, and view the total amount due.

Key Features:
1.Adding Items to the Cart:
Users can add items to their shopping cart by clicking an "Add to Cart" button associated with each product. The application uses Redux to manage the global state, which tracks the items in the cart .

2.Removing Items from the Cart:
Items can be removed from the cart with a simple click of the "Remove" button. This action updates the state managed by Redux, ensuring the cart is always in sync with the user's actions

3.Calculating the Total Amount:
The total amount due is automatically calculated based on the items in the cart. Redux manages this calculation in real-time, ensuring the total is always accurate and up-to-date as users add, remove, or adjust items.

4.Persistent State Management:
Redux provides a centralized state management system that ensures the application's state remains consistent across different components. It handles all state-related actions like adding to the cart, removing items, making the application predictable and easy to debug

5.User Interface:
The UI is built with React.js, providing a seamless, responsive shopping experience. React's component-based architecture allows for reusable and modular code, making it easier to maintain and scale the application.

Workflow:
1.When a user adds an item to the cart, a Redux action is dispatched, updating the cart state in the Redux store. The UI then reflects these changes instantly.

2.Removing an item from the cart dispatches another action that updates the state by removing the selected item and recalculating the total amount
