# Global-Electronics-SQL-database
Table,Field,Description
Sales,Order Number,Unique ID for each order
Sales,Line Item,Identifies individual products purchased as part of an order
Sales,Order Date,Date the order was placed
Sales,Delivery Date,Date the order was delivered
Sales,CustomerKey,Unique key identifying which customer placed the order
Sales,StoreKey,Unique key identifying which store processed the order
Sales,ProductKey,Unique key identifying which product was purchased
Sales,Quantity,Number of items purchased
Sales,Currency Code,Currency used to process the order
Customers,CustomerKey,Primary key to identify customers
Customers,Gender,Customer gender
Customers,Name,Customer full name
Customers,City,Customer city
Customers,State Code,Customer state (abbreviated)
Customers,State,Customer state (full)
Customers,Zip Code,Customer zip code
Customers,Country,Customer country
Customers,Continent,Customer continent
Customers,Birthday,Customer date of birth
Products,ProductKey,Primary key to identify products
Products,Product Name,Product name
Products,Brand,Product brand
Products,Color,Product color
Products,Unit Cost USD,Cost to produce the product in USD
Products,Unit Price USD,Product list price in USD
Products,SubcategoryKey,Key to identify product subcategories
Products,Subcategory,Product subcategory name
Products,CategoryKey,Key to identify product categories
Products,Category,Product category name
Stores,StoreKey,Primary key to identify stores
Stores,Country,Store country
Stores,State,Store state
Stores,Square Meters,Store footprint in square meters
Stores,Open Date,Store open date
Exchange Rates,Date,Date
Exchange Rates,Currency,Currency code
Exchange Rates,Exchange,Exchange rate compared to USD
