# Alma-print-slip bookmarklet

Alma-Print Slip bookmarklet

## What it does

Create a bookmarklet that you can save in your browser bookmark toolbar: when you display in the Alma fulfillment Patron services page the user loans are made and/or displayed just click on the bookmark a loan slip/receipt immediately is displayed and print bypassing the Alma email based circulation desks printers.

## Installation
Generate the bookmarklet here: 

Alma Print Slip Bookmarklet Generator

Drag and drop it in your browser bookmark toolbar (or other bookmark menu if you prefer).

## Configuration

Generating the bookmarklet you can personalize the button and the slip appearance (css and text) and behaviour (display or display and print the receipt immediately): the data are saved locally in a permanent (1 year) cookie when you press "Preview" or "Create the bookmarklet".

## Tips and tricks

If you do not want to display some data (for example, the signature part) simply add a display:none; to the relative css textbox of the element to delete.

Remember that the data displayed in loans table are the same and in the same order of the datas displayed in the table you visualize in the fulfillment Patron services Alma page.

If you use a receipt printer you can check "Two column table" to get a tighter table to print.

If you use Alma in another languange than english please fill the "Sortable translation" field with the word translated in your language (for example, in italian is "ordinabile") to avoid printing it in the loan table. 

You can add a image adding its url: for example, you can add the Alma email logo from Configuration Branding management adding the url https://[...].alma.exlibrisgroup.com/infra/branding/logo/logo-email.png?[...].

In general use your css knowlewdge to personalize all the aspect of the receipts: in case you messed it up, reset the values to the default values.

## Troubleshooting

If your browser blocks the popup you have to allow it from the Alma site.
In chrome the popup position is fixed.



 
