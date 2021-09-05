# ETG-INTERN-IMS
INVENTORY MANAGEMENT SYSTEM in PYTHON WITH JSON  

#In items_added.ipynb

30 products with 5 attributes are stored in dictionary.
  1-Product category
  2-Price
  3-Product name
  4-Product section
  5-Quantity

Quantities can be updated to the dictionary. ( to refill)
Writing the dictionary to json file -Addingrecords.json

#In Billing.ipynb
Reading the Addingrecords.json file which has products_record dictionary.
Using loads() storing the dictionary in rec
storing keys of dict to LIST

DISPLAYING IDS AND PRODUCT NAMES TO USER

In billing Code
# BILLING CODE  
1. Displays ordered product name, id, quantity, date and billing amount
2. Check if id entered matches the id in record
3. Check whether enough quantity is in stock
4. Prompt yes/no if quantity is less than ordered
5. Shows no stock when it is 0
6. Storing the reduced quantity on dict after purchasing.
7. Counting the sales of the day.

Updating record and dumping in JSON file -Productsrecordupdated.json
Productsrecordupdated.json has updated product details ( Storing the reduced quantity on dict after purchasing ) 


