# Database Planning

## Proposed Division of Data

* Data related to each individual item (pictures, description, price, discount, shipping costs, etc.).
* Data related to reviews (pictures from users, ratings, comments, etc.)
* Data related to the store (Store logo, store address, the items the store carries, current inventory, date they joined Etsy, owner name etc.)

## Data Dependencies

### Tammy
* Store Logo; image; etsyStores
* Store name; string; etsyStores
* Total # of items in store; number; etsyStores
* Total Sales; number; etsyStores
* On Etsy Since; number; etsyStores
* Based In; stringl etsyStores
* Item Picture; image; ??
* Item Name; string; ??
* Item Price; number; ??
* Free Shipping; bool; ??
* Free shipping eligible; bool; ??
* Sale percentage; number; ??
* Available # of items; number; ??

## Databases

### Etsy Stores DB - Tammy
* DB: etsyStores (mongo)
* Collection: stores
* Document fields:
  * storeLogo; image
  * storeName; string
  * totalStoreItems; number
  * totalSales; number
  * onEtsySince; number
  * basedIn; string