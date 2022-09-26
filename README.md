This file contains the following:

Drupal Custom Module for Products Content
-----------------------------------------
products

Drupal Custom Block for QR code Display
---------------------------------------
test

Requirements:
------------
PHP 8.1
MySQL8
Drupal9.4.5

Instructions
1. Upload the Products and Test moduels under the following directory 
/drupal/web/sites/all/modules/custom
2. Extract the both compressed files
3. Install the https://github.com/chillerlan/php-qrcode module using composer
4. Enable the both moduels in the Administrator/Extend section
5. Please Install/Enable the theme: Bartik 9.4.6 (default theme)

6. The products module CRUD facility is availebe in the Admin/Configuration/ContentAuthoring/Product Module Settings
7. Ebale/Display the Test Block module to show right side bar 2
8. Change the front page default url is Adminstration/Configuration/Basic Settings/Front Page to the following
		/products/display

9. Thats All. Now go to the home page of the module.
10. If any of the module/products information not displayed, please clear the Cache & Try..
