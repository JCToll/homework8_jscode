HW 8 - JS CODE:
1- Added a "shopping cart" icon from the Font Awesome site - added this to each product. 

2- Clicking on the cart launches the updateCart function which passes one argument= product name

3- The js script has the updateCart function. This takes in the arg (product name), and checks to see if this product is already in the array named containerCart.  
If it does NOT exist, then the "push" function is used to append the product to containerCart array.
If it DOES exist, then it removes the product from the containerCart array using the splice function. 

4- At the end of the function, the array containerCart is sorted alphabetically, then, a new function I wrote (listCart) extracts the array element product names and lists this in the console  as a vertical list --> this is just a summary of all products in the cart. 

Github site:
	https://jctoll.github.io/homework8_jscode/index.html
