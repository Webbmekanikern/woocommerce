#Billmate Payment Gateway for WooCommerce
Forked from [Billmate AB](https://github.com/Billmate/woocommerce) by [Webbmekanikern](http://www.webbmekanikern.se/).

##Description
As we had issues between Billmate and larger companies/organizations, some minor adjustments had to be made.

This repo:

* uses Billmate Invoice Service, instead of Factoring.
* doesn't prefill, prompt or force the customer to use the registered address for the company.
* activates the invoice when the order status is changed to Processing, instead of Completed.
* adds a specific email address field used for invoices.
* populates the invoice fields when the checkout form is re-submited.