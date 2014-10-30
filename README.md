singleidtest
============

Install the app and fill in your details one last time. SingleID will take care of filling in forms from now on.

## Pre-Requirements
1. PHP >= 5.0.0
2. cURL
3. jQuery >= 1.6.1

## How to install
On page where you want to put SingleID plugin you must have jQuery.
Download plugin.php and put it into your webroot directory. Create a folder named userdata in the same directory and make it writtable.

## Configuring
You must to set some settings in the plugin.php
On line XX - XX you must set LOGO_URL ( the logo of your page that will be snown in the user phone when request is sended ), SITE_NAME - the name of your site and requested_data.

requested_data has a values of:<br />
1 - Personal data only
1,2,3 - Personal, Billing and Shipping data
1,-2,3 - Personal, Billing and Shipping data ( Without credit card ) 
1,2,3,4 - Personal, Billing, Shipping and Identification data
1,-2,3,4 - Personal, Billing ( Without credit card ), Shipping and Identification data

<iframe src="plugin.php?op=init" width="200" height="80" frameborder="0"></iframe>

Put this iframe exactly where you want to install the plugin.
