https://vimeo.com/122068883

02:27 create Add to cart button
03:45 cart items path
06:15 specifying the key in the params hash for cart items path
07:30 add cart_items routes
07:50 create cart_items controller
10:45 changing the redirect/ view for the create action; add alert
12:20 adding alert functionality to the views — layouts/application.html.erb
17:00 creating the hash that is the cart within the create action of the cart items controller
24:50 setting default values in a hash when no keys exist
25:40 setting the session
27:30 accessing the sessions hash and displaying to the page with inspect element to see what you’re getting
28:20 persisting cart data
30:11 setting the default value while using persistence
32:42 why using the "edit my cookie” plugin is useful
34:05 accessing the session from the view is a bad idea; create a helper method - load_cart in the application controller
35:35 create a before_action for load_cart
37:10 wrapping instance variables in a method to avoid accessing instance variables directly in the view
38:57 the cleaned up version/ end goal of what the cart should look like
40:45 creating a cart class
44:00  moving memoization functionality into cart class
49:22 refactoring by including an attr_reader for data
