# summer2021-final-project
Final project of the 2nd FrauenLoop cycle on Test Automation - UI Automation for an ecommerce website
(not necessarily covers all of the following points)
URL: http://automationpractice.com/index.php


Homepage 
•	Verify that clicking on the sales banner leads to the correct corresponding page
•	Verify that clicking on “Women” on the sf menu leads to the correct corresponding page
•	Verify that clicking on “Dresses” on the sf menu leads to the correct corresponding page
•	Verify that clicking on “T-shirt” on the sf menu leads to the correct corresponding page
•	Verify that clicking on “Sign in” on the navigation bar leads to the correct corresponding page
•	Verify that clicking on “Contact us” on the navigation bar leads to the correct corresponding page

Sign-in 
•	Verify that there are two options: “Create an account” and “Sign in” after click on “Sign in” on the navigation bar
•	Verify that a relevant error message is displayed when try to log in with invalid credentials (frauenloop@gmail.com; 123)
•	Verify that a user can log in with valid credentials (qqq.test@protonmail.com; 12345)
•	Verify that user’s name is displayed on the navigation bar after login
•	Verify that user can log in in Checkout

Forgot your password
•	Verify that clicking on “Forgot your password” will leads to the correct corresponding page
•	Verify that a relevant error message is displayed when providing an email with an incorrect format (qqq)
•	Verify that a relevant error message is displayed when providing an unregistered email address (frauenloop@gmail.com)
•	Verify that a relevant message is displayed when providing a registered email address (qqq.test@protonmail.com)

Sign-up
•	Verify that a relevant error message is displayed when clicking on the “Create an account” button after filling in an email with an incorrect format. (frauenloop)
•	Verify that after filling in an email with the correct format and clicking on the “Create an account” button, you will be led to the correct page to create an account (frauenloop@gmail.com)
•	Verify that users can create an account after filling in information with accepted formats
•	Verify that relevant error message(s) is/are displayed when information that doesn’t match the accepted formats is provided and users cannot create a new account yet 

Search
•	Search with a keyword based on the product name and verify that the results are relevant. For example: When search for “dress”, the results should only include dresses. 
•	Search with a keyword based on the product color and verify that the results are relevant. For example: When search for “yellow” products, the results should only include products that are available in yellow color.  
•	Search with a valid keyword and verify that the result’s page heading mentions the same key word. When search for “t-shirt”, the result’s page heading is displayed as SEARCH “T-SHIRT”.

Product Page
•	Verify that products’ details are displayed (names, prices, colors, availability statuses)
•	Verify that “Add to cart”, “More” and “Quick view” buttons, “Add to Wishlist” and “Add to compare” hyperlinks are displayed when hover over a product

Quick View Popup
•	Verify that a quick view popup is displayed after clicking on “Quick view” button
•	Verify that product’s basic details are displayed in the popup (big image, name, condition, description, price, color options)
•	Verify that it is possible to change quantity
•	Verify that it is possible to change size

Product Details Page
•	Verify that product’s basic details are displayed (big image, name, condition, description, price, color options)
•	Verify that it is possible to change quantity
•	Verify that it is possible to change size

Shopping Cart
•	Verify that it is possible to add an item to cart from Homepage
•	Verify that it is possible to add an item to cart from Product Page
•	Verify that it is possible to add an item to cart from Quick View Popup
•	Verify that it is possible to add an item to cart from Product Details Page
•	Verify that correct item(s) was/were added to cart
•	Verify that it is possible to change quantity in cart
•	Verify that it is possible to remove item from cart
•	Verify that it is possible to remove item from cart without going to Cart

Checkout 
•	Verify that user can checkout after adding an item to Cart
•	Verify that user can checkout from Cart 
•	Verify that a relevant error popup is displayed and can’t proceed to Payment when user doesn’t tick on the check box to agree to Terms of service

My Account
•	Verify that clicking on user’s name on the navigation bar leads to the correct corresponding page
•	Verify that clicking on “Order History And Details” leads to the correct corresponding page
•	Verify that clicking on “My Credit Slips” leads to the correct corresponding page
•	Verify that clicking on “My Addresses” leads to the correct corresponding page
•	Verify that clicking on “My Personal Information” leads to the correct corresponding page
•	Verify that clicking on “My Wishlists” leads to the correct corresponding page

Contact

Sign Out
•	Verify that it is possible to sign out after clicking on “Sign out” on the navigation bar

