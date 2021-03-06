# Inventory

Once the appropriate category has been created, inventory can then be assigned to that category.

An "Inventory Item" can be anything. The smallest screw, to the biggest transformer. What you wish to store as inventory is entirely up to you.

* [Inventory Fields](#inventory-fields)
* [Adding an Inventory Item](#adding-an-inventory-item)
* [Updating an Inventory Item](#updating-an-inventory-item)
* [Deleting an Inventory Item](#deleting-an-inventory-item)

----

## Inventory Fields
For more information on the fields used throughout the inventory pages, visit the [fields](/inventory/Inventory/fields.md) page.

## Adding an Inventory Item

To add an inventory item:

* Navigate to {{ book.url }}/admin/inventory/home.
* Click `New`
<figure>
    <img src="/assets/add-inventory.png" height="1000" />
    <figcaption>Add an Inventory Item Screen</figcaption>
</figure>
* Enter in the new inventory name first.
* Enter in the inventory SKU.
* The slug (what appears in the address bar) will be automatically generated based on the name.
* If applicable, enter in a description of the new inventory item.
* Does the inventory item belong to another inventory item? If so, select the parent item from the dropdown list.
* Select the appropriate category for the inventory.
* Do you want to publish this inventory? Only published inventory shows on the customer facing website.
* Click `New`.

*Note*: Only the `General` tab is visible when creating an inventory item.

## Updating an Inventory Item

To update an inventory item:

* Navigate to {{ book.url }}/admin/inventory/home.
* Choose the inventory item you wish to edit from the list.
* Make whatever changes are necessary to the inventory item.
* Click `Save`

## Deleting an Inventory Item

__Note: The inventory will deleted permanently and not recoverable.__

Any media (images/files) associated to an inventory item will be permanently deleted.

Deleting an inventory item which has children inventory applied to it will **not** delete any child inventory item. Instead, any children inventory will be reassigned to the `Uncategorized` category.

To delete an inventory item:
* Navigate to {{ book.url }}/admin/inventory/home.
* Choose the inventory item you wish to delete from the list.
* Scroll down to the `Danger Zone` in the `General` tab.
* Click `Delete`.
* Once prompted, confirm you do wish to delete the inventory item.
* Click `Yes, I'm sure`

