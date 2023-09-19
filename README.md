# set-up-ecommerce-tracking-in-Google-Analytics-4
How to set up ecommerce tracking in Google Analytics 4


## What does enhanced ecommerce tracking mean?
The basic ecommerce tracking allows you to see only the purchase data. The enhanced ecommerce tracking enables you to track a few additional steps, such as:

product listing views
product selection
product views
adding the product to the cart
adding the product to the wishlist
viewing the cart
removing from the cart
making a purchase
making a refund
all checkout process steps
promotions views and clicks on them

## What are the differences between UA ecommerce tracking and GA4 ecommerce tracking?
UA Event            GA4  Event         Description

view_item_list      impressions        For listing pages when a user is presented with the results.

productClick        select_item        Whenever a user selects the product in the list of products (listing)

detail

view_item

Whenever a user sees the detail of the product (product page)

addToCart

add_to_cart

Whenever a user adds the product into the cart.

removeFromCart

remove_from_cart

Whenever a user removes the product from the cart

N/A

add_to_wishlist

Whenever a user adds the product into wishlist. The new event added in GA4.

N/A

view_cart

Whenever a user opens the cart. The new event added in GA4.

checkout

begin_checkout

Whenever a user goes through the checkout steps. You could define steps in UA, GA4 has default steps you should follow.

checkout_option

add_shipping_info, add_payment_info

Whenever a user adds shipping or payment info within the checkout process

purchase

purchase

Whenever a user makes a purchase

refund

refund

Whenever a user requests a refund

view_promotion

promoView

Whenever a user sees the promo on your website

select_promotion

promoClick

Whenever a user selects the promo on your website
