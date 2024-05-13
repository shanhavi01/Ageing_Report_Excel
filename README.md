This Ageing Report contains typical mapping data such as food items, size, category, MRP, Cost Price etc. # Ageing_Report_Excel
Ageing data has a mapping sheet with many columns such as product name, product size, category, in production, product shelf life, MRP, and cost price, as well as multiple worksheets for requirements such as ERP dump, product summary, and category summary.
**Ageing Data guidelines are as follows: **
1. The number of days the products have been on the shelf.
2. Sort the products based on their ageing days. The product has been on the shelf for less than six months, six to twelve months, or more than twelve months.
3. The number of products at danger in different storage facilities.
4. Determine the size of the company's financial risk.
5. To what extent can we save expenditures for the business? 
6. Number of unique products
7. Location and product-specific stock count
8. Ageing Analysis Based on Expiry.
**Solution:-**
1.Excel functions such as VLOOK-UP, SUMIFS, COUNTA, IF, REMOVE DULPICATE, and SPLIT THE TEXT INTO TWO PARTS are used to extract valuable insights from data. 
2.Months are converted into days using the formal, month multiple 30.
3.The VLOOKUP function is used to fill the ERP Dump sheet column category, ageing days, and distribute the ageing categories as below 6 months, 6-12 months, and above 12 months.
4.Counting distinct products from the product column using the REMOVE DUPLICATE AND COUNTA functions 
5.Finding location and product-specific stock counts by filtering the data by location, removing duplicate products from the product column, then counting the products with the COUNTA function.
6. Analysing the items' expiry dates on this 01-Sep-19 date using the IF function and sorting them by expired or not expired.
7. Calculate the total pending quantity and ageing category wise using the SUMIFS functions.
