## Test Case: Checkout with empty required fields

### Preconditions:
User is on the cart page with at least one product added to the cart

### Steps:
1. Click the "Checkout" button
2. Leave the payment details fields empty
3. Click the "Place Order" button

### Expected Result:
Validation error messages should be displayed for the required fields and the order should not be placed
