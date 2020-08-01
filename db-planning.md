# Data Planning

## Proposed Division of Data
We will each be 100% responsible for the data we need in our modules.

## Data Dependencies

### Tammy's data dependencies
* Store Logo; image; etsyStores
* Store name; string; etsyStores
* Total # of items in store; number; etsyStores
* Total Sales; number; etsyStores
* On Etsy Since; number; etsyStores
* Based In; string etsyStores
* Item Picture; image; etsyStores
* Item Name; string; etsyStores
* Item Price; number; etsyStores
* Free Shipping; bool; etsyStores
* Free shipping eligible; bool; etsyStores
* Sale percentage; number; etsyStores
* Available # of items; number; etsyStores

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
  * item:
    * itemId; number
    * itemPicture; image
    * itemName; string
    * itemPrice; number
    * itemStock; number
    * freeShipping; bool
    * freeShippingEligible; bool
    * salePercentage; number