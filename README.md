paycoingateway-wpecommerce
====================

Accept Paycoin on your WP-eCommerce powered website with PaycoinGateway.

Download the plugin here: https://github.com/PaycoinGateway/paycoingateway-wpecommerce/

# Requirements

PHP >= 5.3.0 with curl, openssl

# Installation

First generate an API key at https://www.paycoingateway.com/admin/api.html?lang=en. If you don't have a PaycoinGateway account, sign up at https://www.paycoingateway.com/admin/signup.html?lang=en. 

Download the plugin and copy the 'paycoingateway-php' folder and 'paycoingateway.merchant.php' into wp-content/plugins/wp-e-commerce/wpsc-merchants on your server. If upgrading, make sure to remove paycoingateway.merchant.php from wp-content/plugins/wp-e-commerce/wpsc-merchants.

After copying the files, open the Wordpress dashboard and navigate to Settings > Store and click the "Payments" tab. Next, check the box beside "PaycoinGateway", enter your API credentials, and click update.
