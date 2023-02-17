# add_product

`add_product(grocery_data)`

<br>

Adds new grocery product to `grocery_data` based on user input.  
Increments length of `grocery_data` by appending a new list entry in the form `[<name>, <UPC>, <price>, <stock>]` where:
- `<name>` is the new product name as a string
- `<UPC>` is the new product’s 5-digit UPC as an integer
- `<price>` is the price of the new product as a floating-point number
- `<stock>` is the number in stock of the new product as an integer
