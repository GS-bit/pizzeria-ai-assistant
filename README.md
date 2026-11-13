# 🍕 Pizzeria AI assistant
An intelligent virtual assistant for customer service and order management for a fictional pizzeria, built with Python, SQLite and Google Gemini.

Through this software, customers, delivery drivers and cooks can interact with an AI-powered chatbot that represents the pizzeria.

<br>

## ✨ What does this project do?

### 👥&nbsp;&nbsp;For customers:
---

#### 🍽️&nbsp;&nbsp;Browsing the menu:

Customers can check the food offered by the pizzeria at the moment. This allows users to know item names, their descriptions, sizes and prices.


#### 🛒&nbsp;&nbsp;Managing the shopping cart:

Whether it be two pizzas and a soda, the system allows customers to add, remove, edit and review items in their shopping cart before checkout.


#### 🪪&nbsp;&nbsp;Setting the customer's name: 

Every customer has a name, and this name helps delivery drivers to identify the customer more easily.


#### 🏠&nbsp;&nbsp;Setting the delivery location:

It is possible to set the delivery location, which allows the program to evaluate the delivery fee.


#### 💸&nbsp;&nbsp;Allowing payment:

Once the cart is ready, the customer can confirm the order, and the software generates a Pix copy-and-paste code for payment. After the payment is completed, the order is officially registered in the database.


#### 🛵&nbsp;&nbsp;Contacting the delivery driver:

Customers can check their order status ("PENDING", "PREPARING", "OUT FOR DELIVERY", "DELIVERED") and chat with the delivery driver to report any issues.


#### 📢&nbsp;&nbsp;Submitting suggestions and complaints:

Suggestions and complaints are useful for the continuous improvement of the pizzeria, so it's very attractive to have this feature in the system, which stores the customers' opinions in the database anonymously.

<br>

### 📦&nbsp;&nbsp;For delivery drivers:
---

#### 📩&nbsp;&nbsp;Browsing the orders:

Delivery drivers can check active orders in the system. The order information includes: a unique ID, the customer's name, the kinds of products to deliver, the delivery location, the timestamp and the status ("PENDING", "PREPARING", "OUT FOR DELIVERY", "DELIVERED").


#### 💬&nbsp;&nbsp;Contacting the customers and cooks:

They can also talk to the customers and cooks to report any issues.


#### 🧠&nbsp;&nbsp;Using the smart delivery priority:

The system shows the delivery driver the ideal sequence of deliveries, considering the time to deliver the food and the timestamps.

<br>


### 👨‍🍳&nbsp;&nbsp;For cooks:
---

#### 📩&nbsp;&nbsp;Browsing the orders, but with a smart restriction:

As well as delivery drivers, cooks can also check active orders in the system, but the program is interested in showing them only orders that require preparation. So, for example, if a customer orders only a 500 mL soda that is in a freezer, the cooks won't know it. In the orders received by a cook, it is possible to retrieve these information: a unique ID, the customer's name, the kinds of products to prepare, the delivery location, the timestamp and the status ("PENDING", "PREPARING", "OUT FOR DELIVERY", "DELIVERED").


#### 🛵&nbsp;&nbsp;Contacting the delivery drivers:

It's a possibility that cooks need to talk to delivery drivers when an issue appears. Therefore, the pizzeria AI assistant allows this feature.
