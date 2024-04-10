# AI Demystified Shared Files
Files shared with viewers of the AI Demystified webinar for Wyoming SBDC on April 11, 2024.

## Statement of Files
All of the files on this folder are safe to download. They contain no macros.

## File Index

[AccessDatabase / AdventureWorks.accdb](AccessDatabase/AdventureWorks.accdb). The source database from which the spreadsheet examples have been exported.

<hr />

[ProductAndVendors.xlsx](ExcelSpreadsheets/ProductAndVendors.xlsx). Spreadsheet containing 'vwProductOnHand' and 'vwActiveVendorsPerProduct' sheets. This file was used for the **Inventory and Purchasing Combination** example where the items to be re-ordered were found, along with the best vendors for each using the prompt <i>Hi ChatGPT, from the attached spreadsheet, will you please create a list of the products I need to re-order, along with the name of the best vendor for each? The products are listed on the sheet 'vwProductOnHand' and the vendors per product item history is located on the sheet 'vwActiveVendorsPerProduct'. If a vendor can notcannot be found for a product, please list that item as 'Find new vendor'.</i>.

[vwActiveVendorsPerProduct.xlsx](ExcelSpreadsheets/vwActiveVendorsPerProduct.xlsx). Test sheet containing information about individual product purchases from vendors. This sheet was used in ProductAndVendors.xlsx.

[vwProductOnHand.xlsx](ExcelSpreadsheets/vwProductOnHand.xlsx). Test sheet containing on-hand inventory information about every product. This sheet was used in ProductAndVendors.xlsx.

[vwProductSalesSummary.xlsx](ExcelSpreadsheets/vwProductSalesSummary.xlsx). Test sheet that was used to find **Popular Products with the Highest Profit** with the prompt <i>Hello ChatGPT. From the attached spreadsheet, will you please create a list for me containing the five highest profiting products in the list?</i>

[vwRecentSales.xlsx](ExcelSpreadsheets/vwRecentSales.xlsx). Test sheet that could be used to perform a **Sales Customer Analysis** using a prompt similar to <i>Hi ChatGPT, from the attached file of recent sales, will you please list my five best customers?</i>.

