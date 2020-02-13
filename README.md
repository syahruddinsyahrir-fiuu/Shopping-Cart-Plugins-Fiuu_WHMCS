

WHMCS Plugin
===============

<img src="https://user-images.githubusercontent.com/38641542/74416400-0d0da580-4e80-11ea-97da-1f0a349b5731.jpg">

Razer Merchant Services Plugin for WHMCS Shopping Cart developed by MOLPay R&D team.


Supported version
-----------------

WHMCS version v6.0.x


Notes
-----

MOLPay Sdn. Bhd. is not responsible for any problems that might arise from the use of this module. 
Use at your own risk. Please backup any critical data before proceeding. For any query or 
assistance, please email support-sa@razer.com 


Installations
-------------

- Download this plugin, Extract/Unzip the files. 

- Upload or copy those file and folder into your cart root folder

  `<WHMCS Root Directory>/images/logo_molpay.gif`
  
  `<WHMCS Root Directory>/modules/gateways/molpay.php`
  
  `<WHMCS Root Directory>/modules/gateways/callback /molpay_callback.php`
  
- Login to WHMCS Admin Site.

- Click on Setup > Payments > Payment Gateways. 

- On “Activate Gateway” drop down menu, Choose “MOLPay Online Payment Gateway” and click the [Activate] button.

- Fill in your MOLPay Merchant ID and MOLPay Verify Key. You can have the verify key from MOLPay Merchant Profile
 
- Now, access your MOLPay merchant account using the loginID and password provided to you.

- Click on the "Merchant Profile" tab above.

- In the Return URL field enter the following URL:
  
  `<WHMCS Root Directory>/modules/gateways/callback/molpay_callback.php`

- Tick Enable Return URL with IPN to enable IPN on return URL [Optional]

- In the Notification URL field enter the following URL:
  
  `<WHMCS Root Directory>/modules/gateways/callback/molpay_callback.php`

- Tick Enable Notification URL with IPN to enable IPN on notification [Optional]

- In the Callback URL field enter the following URL:
  
  `<WHMCS Root Directory>/modules/gateways/callback/molpay_callback.php`

- Tick Enable Callback URL with IPN to enable IPN on callback [Optional]

- Click on "Update"

- You are done! 


Contribution
------------

You can contribute to this plugin by sending the pull request to this repository.


Issues
------------

Submit issue to this repository or email to our support@molpay.com


Support
-------

Merchant Technical Support / Customer Care : support-sa@razer.com <br>
Sales/Reseller Enquiry : sales-sa@razer.com <br>
Marketing Campaign : marketing-sa@razer.com <br>
Channel/Partner Enquiry : channel-sa@razer.com <br>
Media Contact : media-sa@razer.com <br>
R&D and Tech-related Suggestion : technical-sa@razer.com <br>
Abuse Reporting : abuse-sa@razer.com
