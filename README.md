Hi,

This is a portfolio website optimized for speed.

In order to use it, open "index".html" in your favorite web browser. Click on the links to visit the sub pages.

Enjoy!

For reviewer:

In main.js (that I minified into the main-min.js file), I simply re-used the technique that was showed by Cameron in Elyad's class Website Performance Optimization.
Eliminate the call of document.querySelectorAll(".randomPizzaContainer") by placing it in the variable randomPizzas. Then iterate through this variable to change the size of the pizzas.
