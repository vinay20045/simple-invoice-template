simple-invoice-template
=======================
A clean and simple, 1 page invoice template that let's you generate beautiful invoices without much hassle. The layout is optimized for printing and pdf conversion. It is styled using HTML/CSS and all the functionality comes from using JS. This also means that your invoice data does not leave your browser.

Demo: https://16metrics.com/tools/make_invoice.html

Requirements
------------
JS enabled latest Chrome browser.

Usage
-----
1. Just clone or download the repo and open `make_invoice.html` using the latest chrome browser.   
2. Use the text fields on the right to update details on the invoice.   
3. Click on the print button to print the invoice.   

Modifications
-------------
The invoice template is highly configurable. Here are some pointers in case you want to modify it to fit your needs better...

* The layout uses tables.   
* Page styles are available at the top of file. Some table related styling can be found inline too.
* The JS can be found at the bottom of the page.
* The default values can be changed by changing the values of the text boxes just before the JS section.

External Dependencies
---------------------
The template uses...   
1. https://cdn.jsdelivr.net/jsbarcode/3.3.7/barcodes/JsBarcode.code128.min.js for barcode generation.   
2. https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,800,300italic,400italic,600italic for open sans font.

Workling & Limitations
----------------------
1. The template is tested only on Chrome browser.   
2. Total units, Sub total and Grand Total cannot be entered manually.
3. Once an item is added, it can only be modified but cannot be removed.
4. Serial numbers for the items are auto generated.

Issues
------
Please raise an issue on github or send me a mail at vinay@askvinay.com