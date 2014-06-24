# Webly Assignment README #

###Task 1###

* The answers are in comments above the code

###Task 2###

* I have included the scenario where there is inventory of the jewellery. Right now, given the data, the app will open up to a screen where it shows the earrings are out of stock and you cannot place an order.
* Added a side menu for additional functionality for future addition of products.
* If the product is made available by using the stock.inStock property, then a whole load of features can be used. For instance, adding to cart pops up a checkout menu on the top. On clicking the checkout menu you can review your order etc. You could proceed to payment from there else continue shopping. There is a way to empty the cart as well.
* Good enhancements would be to have quantity change in the checkout page. Also, ability to delete only a single item from the cart would be another enhancement. Also, a grid of the products present in the category would be good.

##Screenshots of the App##

![alt text](https://db.tt/vgVUie7z "Landing Page" =245x475) ![alt text](https://db.tt/9whGAwj6 "Landing Page" =245x475)
![alt text](https://db.tt/Ki2sIevU "Checkout Page" =245x475) ![alt text](https://db.tt/Pr0xvldR "Landing Page" =245x475)



###Task3###

* The testing has been done for a "Marisa Platinum ring" on m.kamajewellery.com. The placement of the order isn't taking place, after selecting COD as payment methods, even after setting a custom timeout of 30 seconds on the waitForSelector method of CasperJS.
