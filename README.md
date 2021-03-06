== Description ==

Order Tip for WooCommerce is a plugin which allows customers to add a tip or donation to a WooCommerce order. The tip is added under the form of a WooCommerce fee.

It allows the tip to be a percentage of the order total or a fixed custom amount. Cash tip is also available which marks the tip as 0 in value, but you should expect a tip on the delivery of your products or on the pickup of the order by the customer.

There is also an option for custom tip which brings up a text field where the customer is able to type in a custom amount and which is subsequently added as a fixed amount. 

The tip can also be set to be taxed or not as per your current Tax options set in WooCommerce. It features 6 standard tip rates (5, 10, 15, 20, 25, 30).

It features various configuration options in the WooCommerce Settings panel under the tab Order Tip.

The plugin's backend is translated in German, Swiss German, Spanish, French, Italian and Romanian.

= Check out a demo here: =

(https://order-tip-for-woocommerce.tudorache.me/

= Check out a video on installing and using the plugin =

https://www.youtube.com/watch?v=9CskEO7oQV8

= Important Notes =

The plugin works out of the box, with no coding skills required on basically any theme. However, it uses JavaScript for adding the tip to the order. If for some reason it doesn't work as expected, please check your browser's console for any JS errors or drop a line here in the Support tab providing a link to your website.

= Developers =

There are a couple of filters you can hook into should you need to extend or edit the core functionality:

wc_order_tip_title - takes in 1 string variable which holds the title of the form which appears before the form;

wc_order_tip_rates - takes in 1 array variable which holds the values of the predefined standard tip rates. You should return a simple array containing the values you wish to add. Eg: array( 10, 15, 30 ).

== Installation ==

1. Upload and activate plugin in your WP installation
2. Go to WooCommerce -> Settings -> Order Tip
3. Configure the plugin and save the settings
4. Check the frontend cart page and checkout page
