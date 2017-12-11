# coolshop-application-assignment-frontend
In this README you will find a set of assignments. They will consist of a part with a set amount of tasks to be completed, and a part where you can let your imagination run wild.

Please do not hand in your solutions by means of a pull request. Instead, send us the code, for example by uploading it to Dropbox or a similar service.

Since this is a frontend related assignment, we also recommend you upload the code somewhere, where we can actually see it running, and provide us with the URL.

While solving these exercises, keep a focus on frontend-related technologies - both JavaScript and styling. For example, instead of solving some issue with a backend using for example PHP or Python, focus on solving it solely using JavaScript (for example, use local storage for persistence if possible).

## Exercise A

For this exercise you will find in the repository a file named `products.json`. In this file you will find a list of products, in a format that somewhat resembles what Coolshop uses in production.

* Design a view that lists all the products in `products.json`. Consider this a "search view". This should show as much information as you find necessary, but at minimum image, title and price
* In the JSON file you will not find the image. In order to find this, you can use the JSON URL listed for each product - this endpoint will output the image
* Make it possible to filter and/or sort. This could be filtering on product conditions (new, used) and sorting on prices
* Create a simple way to search for products in the listing

## Exercise B

In this exercise you can freely think up more ways to expand on exercise A. Possible scenarios could be, but is not limited to:

* Make it possible to click on a product and go to an actual product page
* Implementing a basket/cart, and make it possible to add items to the cart