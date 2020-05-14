# Lab 14 -
- Do not modify the HTML files

## The `index.html` is an order form for customers: it will have an order 
1. A dropdown menu of all BusMall products(`<select>` and `<option>` will be needed).
1. An input of `type="number"` to indicate the quantity to purchase. 
1. An "Add to Cart" button to submit the oder. When the order is submitted. all of the input fields should be cleared.
1. An animated confirmation message using CSS and JS, displayed when the order is submitted. puls a link to the shopping chart page.
1. Appropriate instructions and styling on the page. 

## `cart.html` page will display the BusMall orders on a typical shopping cart checkout page.
1. It should display all items currently in the order with a picture of the item.
1. Each order should have a button "Delete this item" that will remove that order from the DOM ( and array of ordered items) when it is clicked. 
1. Text inputs for name, street, city , state, ZIP code, and phone number.
1. An input of `type="number"` to enter a 16-digit credit card number
1. A "Process Order" button to submit the order. When the order is submitted. all of the input fields should be cleared.
1. An animated confirmation message using CSS and JS.
- Some things to think about
1. You'll need to use local storage to share data between the 2 HTML pages.
1. The constructor from BusMall might be handy as a way to organize your products.
1. 