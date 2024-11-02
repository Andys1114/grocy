> ⚠️ xxxBREAKING CHANGESxxx

> ❗ xxxImportant upgrade informationXXX

> 💡 xxxMinor upgrade informationXXX

### New feature: xxxx

- xxx

### Stock

- Added a new product picker workflow "External barcode lookup (via plugin)"
  - This executes the configured barcode lookup plugin with the given barcode
  - If the lookup was successful, the product edit page of the created product is displayed, where the product setup can be completed (if required)
  - After that, the transaction is continued with that product
- Optimized form validation (max amount checks) related to unit conversion with a lot of decimal places on the consume and transfer page
- Optimized that the stock report "Spendings" now excludes self produced products (thanks @danielr18 for the initial work on this)
- Fixed that when copying a product, the field "Treat opened as out of stock" wasn't copied along (thanks @TheDodger)
- Fixed that the product groups filter on the master data products page used a contains search instead of an exact search
- Fixed that Scan Mode on the purchase and consume page didn't work (not all fields were properly populated) when using/scanning a product Grocycodes

### Shopping list

- xxx

### Recipes

- When self producing a product ("Produces product" recipe option) the name of the recipe is now added to the note field of the created stock entry
- Fixed that when `FEATURE_FLAG_STOCK_STOCK` was set to `false`, the "Put missing products on shopping list"-button was not visible
- Fixed that scanning a product barcode on the recipe ingredient edit page didn't work
- Fixed that the recipe edit button on the recipes page gallery view didn't work

### Meal plan

- xxx

### Chores

- xxx

### Calendar

- xxx

### Tasks

- xxx

### Batteries

- xxx

### Equipment

- xxx

### Userfields

- Userentity tables (custom objects / lists) now also have the table options icon (top left corner eye icon, to e.g. add a grouping condition)

### General

- xxx

### API

- Optimized that uploading files where the file name contains non-ASCII characters is now also possible
