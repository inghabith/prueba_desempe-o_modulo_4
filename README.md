# prueba_desempeño_modulo_4

Project description.
## Technologies used.
-PGadmin
## Database engine used.
-Postgres sql

## Explanation of normalization process.
We have a simple, disorganized Excel spreadsheet containing relevant data—likely related to the marketing and distribution (buying and selling)—of various hardware products involving different suppliers across different cities.

The initial table exhibits multiple flaws that render it an inefficient database. First, there is data duplication and redundancy; for instance, two tables (`supplier_city` and `warehouse_city`) represent the same information—city names. Second, there are inconsistencies in how the same data is recorded—such as in the `supplierName` field, where the same supplier appears under different spellings; similar issues occur in the tables for cities, products, and categories. While variations in product pricing might be considered normal, it is worth noting that the unit price data for the same supplier lacks consistency, fluctuating significantly over very short periods.

The following entities are identified.
• riwi_categories.
• riwi_products.
• riwi_cities.
• riwi_warehouses_sites .
• riwi_warehouses_cities
• riwi_suppliers
• riwi_suppliers_cities
• riwi_purchase_order
• riwi_purchase_details

## Database structure.

## Instructions to create the database.


• Instructions to load data.
1- Locate the SQL file.
2. Open pgAdmin3 and locate the server.
4. Right-click on the server --> Restore.
5. Browse for the SQL file at its location.
6- Load the backup.

• Explanation of each SQL query.


• Developer information:
- HABITH JOSE DE LEON DIAZ
- CLAN MAGDALENA
