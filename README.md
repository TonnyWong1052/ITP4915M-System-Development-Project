# ITP4915

TESTING ACCOUNT:
```
ACCOUNT: sales
PASSWORD: sales
```

# Demon
![Login](https://github.com/TonnyWong1052/ITP4915/blob/main/demon/Login.png)
![POS](https://github.com/TonnyWong1052/ITP4915/blob/main/demon/pos.png)
![editOrder](https://github.com/TonnyWong1052/ITP4915/blob/main/demon/editOrder.png)
![editOrder2](https://github.com/TonnyWong1052/ITP4915/blob/main/demon/editOrder-1.png)
![ManagerSendRequest](https://github.com/TonnyWong1052/ITP4915/blob/main/demon/storeManager.png)


# Functional Requirements
## Sales staff function:
- Add product to shopping cart function (requirements: click add button).
- Adjust product quantity function (requirements: after adding product to the shopping cart). 
- Payment/ making order function (requirements: after adding product to the shopping cart and editing the quantity, user click “pay” button). 
- Select different order type function (including:  pick-up, Booking and delivery)
-	Select different payment method function (including: cash and credit card)
-	Print the receipt function (receipt format: PDF)
-	Watch customer order function (including: order id, price, customer name, phone number and order type)
-	Edit customer order function (allow editing: Customer Name, Gender, Phone).
-	Refund function (requirements: after clicking the Edit order)
-	Show Delivery Detail function (including: Delivery ID, order ID, Delivery Date, Arrive Date, Driver Name, installer Name, Delivery Status, Installation Status and Address).

## Sales manager function
- Replenishment request function (Make a request to the Inventory Department)
- Edit store detail function (allow editing: city, contact, address and email).
- Report Problem function (notes: If the product is defective, staff can report to another department).

## Inventory staff function
-	add manufacturer function (filling: manufacturer ID, Manufacturer Name, City, Phone No, URL, Email, Address)
-	add product function (filling: product name, manufacturer ID, product ID, price, weight(kg), width(cm), Height(cm), Length(cm) and Describe. Place: product Images).
-	Edit product function (allow editing: product name, manufacturer ID, product ID, weight(kg), width(cm), Height(cm), Length(cm) and product describe. Place: product Images).
-	Delete product function (requirements: select a production in product list).
-	Stock in/out function (requirements: select a product id and property id).
-	Display product detail and stock in/out in the respective shop (requirement: select a property ID).
-	Display product detail and stock in/out in the respective warehouse (requirement: select a property ID).
- Create delivery order (requirements: delivery ID, order ID, start date, arrive date and address. option: installation).
-	Display delivery order function (including: delivery ID, order ID, start date, arrive date, address installation status).
-	Delivery edit/delete function (allow editing: driver name, installation name)
-	Choose delivery man and installers function 

## Inventory manager function (The inventory Manager has all the features of an Inventory Person.)
-	Setting stock level function (manager can set a different stock level. If product quantity is lower than the setting level, the system will prompt).
-	Purchase product function (requirements: purchase ID, product ID, date time, cost and quantity).
-	Editing purchase product function (allow editing: product id, date time, cost, quantity).
-	Delete purchase product function (requirements: select purchase ID).
-	Generate daily delivery document function (requirements: select date. document format: PDF).

## Account staff and manager function:
-	Data analysis function (a bar chart).
-	Problem review (requirements: select feedback ID).

## Admin function:
-	Add account function (filling: account ID, staff ID, password, Property ID and Permission. Selection: account lock/unlock). 
-	Delete account function (selection: staff ID)
-	Edit account function (allow editing: account ID, staff ID, password, Property ID, Permission and account lock).
-	Add staff function (filling: staff, name, phone no, email, position, address. selection: department. Placing: personal icon.)
-	Delete staff function (selection: staff ID)
-	Edit staff information function (allow editing: staff, name, phone no, email, position, address, department, personal icon.).

