**********************************************************************************************
*****  VERSION 1.55 IS THE DEFAULT BRANCH AS OF 8/10/2018 *****
**********************************************************************************************

#SayNoToInfoPath with StratusForms! A lightweight InfoPath alternative for SharePoint 2007,2010,2013,2016, and Office 365

Watch the video to get started: https://youtu.be/OIjevmlzCFc

Documentation located at: http://www.stratusforms.com/documentation/

This work is licensed under a Creative Commons Attribution-NonCommercial 3.0 Unported License. 

*********************** IMPORTANT NOTICE ABOUT LICENSING **************************************
* STRATUSFORMS IS FREE UNLESS YOU ARE BUNDLING IT IN A PRODUCT THAT IS TO BE SOLD             *
*                                                                                             *
* YOU MAY USE STRATUSFORMS FOR FREE FOR ANY INTERNAL PROJECTS, OR AS A CONSULTANT DOING WORK  *
* FOR A CLIENT. SUBMIT ANY QUESTIONS ON LICENSING TO INFO@STRATUSFORMS.COM                    *
*                                                                                             *
***********************************************************************************************

Do you want to use this product for a personal, internal, or non-profit project? 
Then you can use it for free under the Creative Commons Attribution-NonCommercial 3.0 License. 
http://creativecommons.org/licenses/by-nc/3.0/

All samples are provided as-is with no warranty.

For paid support please contact info@stratusforms.com

/*******************************************

WHAT'S NEW IN VERSION 1.55

- General tweaks
- Created a special Comments field type to track comments by user
- Fixed issue with element id's when there are multiple repeating content sections
- List items can be created without a pre-existing StratusFormsData field
- View Forms can be created for SharePoint Lists that do not have a StratusFormsData field
********************************************/

This work is licensed under a Creative Commons Attribution-NonCommercial 3.0 Unported License. 

Do you want to use this product for a personal, internal, or non-profit project? 
Then you can use it for free under the Creative Commons Attribution-NonCommercial 3.0 License. 
http://creativecommons.org/licenses/by-nc/3.0/

All samples are provided as-is with no warranty.

For paid support please contact info@stratusforms.com


Stratus Forms for SharePoint Basic Usage:

1) Create a list to store form data
2) Create a field in this list with the name StratusFormsData.  This field *MUST* be a PLAIN TEXT MULTILINE FIELD
3) Create an HTML file for your form with the correspondging JavaScript and CSS as needed (see examples for... well... examples)
4) Upload this file somewhere that can be referenced in SharePoint (I typically use the Site Assets Document Library)
5) Create a page in SharePoint
6) Add a Content Editor Web Part to the page
7) Link the Content Editor Web Part to your form created in step 3
8) Ta Da!

For more information visit our web site at www.stratusforms.com
Send an email to info@stratsuforms.com to request access to our Slack Team for support and updates
