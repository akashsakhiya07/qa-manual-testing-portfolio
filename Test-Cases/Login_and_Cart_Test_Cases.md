# Login and Cart Test Cases

This document contains manual test cases written for basic login and cart functionality of the e-commerce application.

---

## Test Case 1: Verify Login with Valid Credentials

Test Case ID: TC_LOGIN_01  

Steps:
1. Open the application homepage  
2. Click on "My Account" and select "Login"  
3. Enter valid email and password  
4. Click on the Login button  

Expected Result:
User should be logged in successfully and redirected to the account dashboard.

---

## Test Case 2: Verify Login with Invalid Credentials

Test Case ID: TC_LOGIN_02  

Steps:
1. Open Login page  
2. Enter invalid email or password  
3. Click on Login  

Expected Result:
An error message should be displayed indicating invalid login credentials.

---

## Test Case 3: Verify Add to Cart Functionality

Test Case ID: TC_CART_01  

Steps:
1. Search for a product (e.g. iPhone)  
2. Click on the product  
3. Click on "Add to Cart" button  

Expected Result:
Product should be added to the cart and a success message should be displayed.

---

## Test Case 4: Verify Cart Page Displays Added Product

Test Case ID: TC_CART_02  

Steps:
1. Add a product to the cart  
2. Click on the cart icon  

Expected Result:
Cart page should display the added product with correct details.
