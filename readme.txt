=== WooCommerce Discounts Plus ===
Contributors: Fahad Mahmood
Tags: woocommerce, discounts, percentages, criteria, sales, sales booster, woocommerce discounts, woocommerce sales
Requires at least: 3.5
Tested up to: 4.0
Stable tag: 1.0
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

An amazing WooCommerce extension to implement multiple discount criterias with ultimate convenience.

== Description ==

An amazing WooCommerce extension to implement multiple discount criterias with ultimate convenience.


WooCommerce Discounts Plus is compatible with WooCommerce 2.0.x to 2.2.x.

Let us examine some examples of usage.

*   You may want to feature the following discount policy in your store: if the customer
orders more than 5 items of a given product, he/she will pay the price of this order
line lowered by 10%.

*   Or you may want a different policy, for example offering a 5% discount if the customer
orders more than 10 items of a product and a 10% discount if he/she orders more than
20 items.

*   Discounts Plus supports flat discounts in currency units as well,
enabling you to handle scenarios like deducting fixed value of, say $10 from the item subtotal.
For example, when the customer orders more than 10 items (say, 15, 20, etc.), a discount of $10
will be applied only on the subtotal price.

The settings for discounts are simple yet extensive, allowing wide range of discount
policies to be adopted in your store.

Here is the list of the main features:

*   Possibility of setting percentage Discounts Plus or flat (fixed) Discounts Plus in currency units.
*   Discounts Plus for product variations is supported to treat them separately or by shared quantity when discounting. 
*   Discount is better visible and is available on several locations (see below).
*   Discount is visible on the Checkout page
*   Discount is visible on the Order Details page
*   Discount is visible in WooCommerce order e-mails and invoices as well.
*   Showing the applied discount when hovering over the item price in the cart.   
*   Possibility of easily changing the CSS of the price before and after discount.
*   Discounts Plus can or cannot be applied if a coupon code is used, depending on configuration.
*   HTML markup is allowed in information about the Discounts Plus offer in Product Description.
*   Discounts Plus can be disabled more easily in the Product Options page.
*   Compatibility with all WooCommerce versions.

** If you like WooCommerce Discounts Plus, please also check out more premium plugins: **

*   <a href="http://shop.androidbubbles.com">Go Premium</a>


== Installation ==

1. Download the latest version and extract it in the /wp-content/plugins/ directory
2. Activate the plugin through the 'Plugins' menu in WordPress

Once the plugin is activated, you can use it as follows:

1. First navigate to WooCommerce settings. Under the Discounts Plus tab, find the global
configuration for Discounts Plus. Make sure "Discounts Plus enabled" is checked and optionally
fill information about discounts which will be visible on the cart page. You can include HTML
markup in the text - you can, for instance, include a link to your page with your discount
policy. In case you need the plugin to work well with product variations, make sure that the
"Treat product variations separately" option is unchecked. Since version 2.0 you
may choose to use a flat discount applied to the cart item subtotal. Optionally you may also
modify the CSS styles for the old value and the new value which is displayed in the cart.
Save the settings.

2. Navigate to Products and choose a product for which you want to create a discount policy.
In the Product Data panel, click Discounts Plus and optionally fill information about the discount
which will be visible in the product description.

3. Click "Define discount criteria" button to create a policy. Quantity (min.) means minimal
number of ordered items so that the (second textbox) Discount applies. It is possible to
add up to five discount lines to fine-tune the discount setting.

== Frequently Asked Questions ==

= Are multiple discounts supported? How many levels of discounting may be applied? =

Yes, multiple discounts (related to a single product) are supported. Currently it is possible to
set up to 5 discount lines. That should be enough for reasonable fine-tuning of the discount.

= Is only a percentage discount implemented? =
Since version 2.0 another type of discount is added, allowing you to set a fixed discount in currency units
for the cart item subtotal.

= Will the discount be visible on WooCommerce e-mails and Order status as well? =
Yes. Since version 2.0, this feature has been implemented.

= Is it possible to handle discount for product variations as a whole? =
Yes, in case you have several product variations in your store and you need to apply the discount
to all the purchased variations, please upgrade to the latest version of Discounts Plus.
This functionality can be disabled in Discounts Plus settings.

= Is the plugin i18n ready? =
Yes, the plugin supports localization files. You can add support for your language as well by the standard process.

= Can you provide an example of setting a percentage Discounts Plus? =
Sure. Below is an example of setting a Discounts Plus for a product with three discount lines. 

1. Quantity (min.) = 3, Discount (%) = 5
2. Quantity (min.) = 8, Discount (%) = 10
3. Quantity (min.) = 15, Discount (%) = 15

If the customer orders, say, 12 items of the product which costs $15 per item, the second
discount line will apply. The customer then pays 12 * 15 = 225 dollars in total minus
10%, which yields $202.5. Note that this discount policy only applies to the concrete product -- other
products may have their own (possibly different) discount policies.

= Can you provide an example of setting a flat Discounts Plus? =
Example for flat discount follows:

1. Quantity (min.) = 10, Discount ($) = 10
2. Quantity (min.) = 30, Discount ($) = 20

If the customer orders, say, 15 items of the product which costs $10 per item, the first discount
line will apply and the customer will pay (15 * 10) - 10 dollars. If the customers orders
50 items, the second discount line will apply and the final price will be (50 * 10) - 20 dollars.
Setting Discounts Plus couldn't have been easier.

== Screenshots ==
1. WooCommerce Settings Area
2. WooCommerce Products Listing
3. WooCommerce Product Discount Criterias
4. WooCommerce Cart View - Need Discounts? (Pro Feature)
5. WooCommerce Cart View - Need Discounts? Clicked (Pro Feature)
6. WooCommerce Cart View - Discount Option Selected (Pro Feature)
7. WooCommerce Cart View - Discounts On Multiple Products (Pro Feature)
8. WooCommerce Cart View - Boost Your Sales With This Plugin (Pro Feature)
9. WooCommerce Cart - Order Review (Pro Feature)


== Changelog ==

= 1.0 =
* Releasing 1.0 version.

== Upgrade Notice ==

= 1.0 =
Releasing 1.0 version.
