# ga4-ecom-attributor
Updates of other ready made GA4 ecom attributors, using only localStorage and improving error handling.

The utility will trigger on the following events:
- add_to_cart: If it includes a item_list_name, it will save/possibly overwrite the item_list_name keyed with the item_id
- select_promotion: Will overwrite promotion_id, creative_name, creative_slot
- gtm.dom + purchase: It will remove any stored items purchased, it will also clear the promotion data
- gtm.dom: It will scrub the local storage and remove expired items

How to use:

