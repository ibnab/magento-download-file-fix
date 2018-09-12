# Admin File Download Fix For Magento 1.9.x #

In some circumstances the URL for uploaded Custom Option files returns a 404.
This is because Magento removes the sales_quote_item reference but leaves the file intact.

This hack creates a direct download link to the file and uses the HTML "download" attribute to assign the correct filename.

Author: Anthony B. Earles (tony@icgonline.co.uk)

