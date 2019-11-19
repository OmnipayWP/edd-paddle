=== Easy Digital Downloads - Paddle Gateway ===
Donate link: https://omnipay.io/downloads/edd-paddle-payment-gateway/
Tags: paddle, paddle payment, paddle checkout, easy digital downloads, edd, payment, payment gateway, gateway, paddle payment gateway, paddle gateway, credit card, paypal, pay, online payment, shop, e-commerce, ecommerce
Requires at least: 4.0
Tested up to: 5.3
Stable tag: 1.2.8
License: GPL-2.0+

Accept a wide range of global payment methods including all major Credit Cards, PayPal, ApplePay and Wire Transfers (ACH/SEPA/BACS).

== Description ==
A payment gateway that allows your Easy Digital Downloads powered store / e-commerce website to accept credit card, ApplePay and PayPal payment via Paddle.

[Click to see a demo](https://omnipay.io/edd-demo/)

### Features
* Accept credit card payment.
* Accept PayPal payment.
* Accept ApplePay payment.
* Wire Transfers (ACH/SEPA/BACS).
* Well coded with best practices in mind.
* No technical skills needed.
* Easy to use and customize.


== Installation ==

Navigate to your WordPress "Plugins" page, inside of your WordPress dashboard, and follow these instructions:

1. Login to your WordPress dashboard.
1. Navigate to **Plugins > Add New** and click on the "Upload Plugin" button.
1. Choose the plugin zip file and click "Install Now".

== Frequently Asked Questions ==

Have any question, shoot us a mail via support[at]omnipay.io

== Changelog ==

= 1.2.8 =
* Fixed bug where VAT refunds caused payment/subscription to be refunded/cancelled in EDD
* Fixed: declaration of case insensitive constant in defined() is deprecated

= 1.2.7 =
* Added self healing when there is a missing associated plan ID for a subscription.
* Fixed bug where 0 amount payment wasn’t added to edd record.
* Remove discount option in paddle checkout for edd cart checkout.

= 1.2.6 =
* Fixed bug where subscription refund didn’t set the payment as refunded.

= 1.2.5 =
* Fixed issue where multiple payments records were created for a single order.
* Fixed issue where multiple license keys are generated for a single payment.

= 1.2.4 =
* Fixed detected race conditions issues.

= 1.2.3 =
* Fixed bug with recurring buy now purchase not working for non logged users.

= 1.2.2 =
* Fixed issue where amount update from webhook is zero.
* Fixed issue where subscription wasn't created on buy now checkout.

= 1.2.1 =
* Fixed bug where sub wasn’t cancelled on upgrade.
* Fixed issues with Buy Now button checkout.

= 1.2 =
* Fixed bug where user weren't being assigned to payment.
* Fixed subscription buynow payment.
* Fixed Call to undefined function get_plugin_data()
* Added site url to auth app name.

= 1.1 =
* Added option to create account for non-recurring product via buy now checkout
* Fixed race condition in webhook handler

= 1.0 =
* the genesis
