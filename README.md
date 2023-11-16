# Shopify_API_Google_Sheets_App_Script
Pull the last 30 days or revenue (Date and Revenue), product sales (Product, Revenue, Units Sold and Sale Date) and order history (Order ID, Customer Name, Amount and Date) into a Google Sheet

Need to update with your store domain on this line:
  var apiUrl = "https://ENTER HERE.myshopify.com/admin/api/2023-01/orders.jso

Need to update with your Shopify-Access-Token on this line:
  "X-Shopify-Access-Token": "ENTER HERE",

Need to set up a google sheets with the pages Daily Revenue, Product Sales and Largest Orders
Each page needs to have the headers mentioned above for the corresponding page. 

