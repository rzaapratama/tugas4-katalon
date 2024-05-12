Test Case 1: Login to SauceDemo

Step 1: Open Browser
Command: Open Browser
Target: https://www.saucedemo.com

Step 2: Enter Username
Command: Set Text
Target: id=user-name
Value: standard_user

Step 3: Enter Password
Command: Set Text
Target: id=password
Value: secret_sauce

Step 4: Click Login Button
Command: Click
Target: id=login-button

Step 5: Verify Login Success
Command: Verify Element Present
Target: css=.app_logo


Test Case 2: Add Product to Cart

Step 5: Select Product
Command: Click
Target: css=.inventory_item:nth-child(1)

Step 6: Add Product to Cart
Command: Click
Target: css=.btn_primary.btn_inventory

Step 7: Verify Product Added
Command: Verify Text Present
Target: css=.shopping_cart_badge
Value: 1
