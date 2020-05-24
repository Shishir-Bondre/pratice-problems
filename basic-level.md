# Basic Level

## Introduction

 - This are the basic level problems which any begineer level programmer can use for pratice.  
 - The intention behind this list is used get used
   to programming language syntax and make the most of it. 
 - This can be either a comand line interactive programs (or) libary.
 - Ethier of the programming approach can be used, but recommeded would be that just start with the basic of solving the problem first, then making it elegant.

 

## Problems

 1. **TODO List**
 
      Create a list where a user can perfom below actions
	 
	 - Add a item to list with 
		 - Name: Title of item (max 200 chars)
		 - Description: Plain text (max 1000 chars) 
	 - Retrive items from the list by 
		 - All items
		 - Item by name or id 
	 - Delete item from list by 
		 - All items
		 - Item by name or id 
	 - Update the items (select the item either by id, name)
	
	**Note**
	Id should be unique for each item in the list
---------------------------------------------------------------------

2. **Ticket Booking problem**

	Create a platforn wherein a **user/retailer/seller** can list the online tickets (example event tickets, bus tickets, movie tickets etc etc) and the **end user/customer/buyer** can buy/book the listed tickets

	- **retailer** adds the list(s) of tickets
		- Items details (item category, item name, item description, item price, item quantity [number of tickets], other details)
	- **retailer** can modify the list
		- By id or item name
	- **retailer** can delete/mark expired the list(s) of ticket(s)
		- By id or item name
	- **seller** can add the list(s) of ticket(s) to cart
		- Can add ticket(s) to the cart
		- Can delete the ticket(s) from the cart
		- Can update the ticket(s) by quantity in cart
	- **seller** 
		- Can finally pay for the cart
	- **seller** 
		- Can unbook/delete the booked/paid ticket(s)

	**Note**:
	- This is only for the ticket booking
	- Payment integration is out of Scope
	- Data base integration is out of Scope
	- This problem tries to improve your data structures, basic schema daigram,  programming
	- Adavance usage such as design patterns is your choice, but focus is on basic first

---------------------------------------------------------------------------------------------

3. **ACL problem** (Access control list)
