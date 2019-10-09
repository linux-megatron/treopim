# Channels

**Channel** – a destination point for your product data, which can be synced with third-party systems as well as exported in certain formats. Generally, a channel is a place, where your product information should appear; for example, your online shop, mobile app or print catalog.

Using channels allows you to implement your multichannel or omni-channel strategy in a more efficient way.

## Channel Fields

The channel entity comes with the following preconfigured fields; mandatory are marked with *:

| **Field Name**           | **Description**                            |
|--------------------------|--------------------------------------------|
| Active				   | Activity state of the channel record                 |
| Name (multi-lang) *	   | Channel name                   |
| Code *                   | Unique value used to identify the channel. It can only consist of lowercase letters, digits and underscore symbols     |
| Currencies *			   | Multiselect-list of currencies. The prices in the defined currency (or currencies) will be transferred via the given channel  |
| Description			   | Description of the channel usage    |

If you want to make changes to the channel entity, e.g. add new fields, or modify channel views, please contact your administrator.

## Creating

To create a new channel, click `Channels` in the navigation menu to get to the channel [list view](#listing), and then click the `Create Channel` button. The common creation window will open:

![Channel creation](../../_assets/channels/channels-create.jpg)

Here enter the desired name for the channel being created and activate it, if needed. Its code is automatically generated based on the entered name, but you can change it via the keyboard. Define the currencies to be used in prices for the given channel using the corresponding drop-down list. Also select the channel owner and assigned user from the corresponding lists. The channel description is an optional field and can be left empty.

*Please, note that the `Currencies` list is set up by the administrator.*

Click the `Save` button to finish the channel creation or `Cancel` to abort the process.

If the channel code is not unique, the error message will appear notifying you about it.

Alternatively, use the [quick create](https://treopim.com/help/user-interface) button on any TreoPIM page and fill in the required fields in the channel creation pop-up that appears:

![Creation pop-up](../../_assets/channels/creation-popup.jpg)

## Listing

To open the list of channels available in the system, click the `Channels` option in the navigation menu:

![Channels list view page](../../_assets/channels/channels-list-view.jpg)

By default, the following fields are displayed on the [list view](https://treopim.com/help/views-and-panels) page for channels:
 - Name
 - Code
 - Active

To change the channel records order in the list, click any sortable column title; this will sort the column either ascending or descending. 

Channels can be searched and filtered according to your needs. For details on the search and filtering options, refer to the [**Search and Filtering**](https://treopim.com/help/search-and-filtering) article in this user guide.

To view some channel record details, click the name field value of the corresponding record in the list of channels; the detail view page will open showing the channel records and the records of the related entities. Alternatively, use the `View` option from the single record actions menu to open the [quick detail](https://treopim.com/help/views-and-panels) pop-up.

### Mass Actions

The following mass actions are available for brand entities on the list view page:

- Remove
- Mass update
- Export
- Add relation
- Remove relation

![Channels mass actions](../../_assets/channels/channels-mass-actions.jpg)

For details on these actions, refer to the **Mass Actions** section of the [**Views and Panels**](https://treopim.com/help/views-and-panels) article in this user guide.

### Single Record Actions

The following single record actions are available for channel entities on the list view page:

- View
- Edit
- Remove

![Сhannels single record actions](../../_assets/channels/channels-single-actions.jpg)

For details on these actions, please, refer to the **Single Record Actions** section of the [**Views and Panels**](https://treopim.com/help/views-and-panels#single-record-actions) article in this user guide.

## Editing

To edit the channel, click the `Edit` button on the detail view page of the currently open channel record; the following editing window will open:

![Channel editing](../../_assets/channels/channel-edit.jpg)

Here edit the desired fields and click the `Save` button to apply your changes.

Besides, you can make changes in the channel record via [in-line editing](https://treopim.com/help/views-and-panels) on its detail view page.

Alternatively, make changes to the desired channel record in the [quick edit](https://treopim.com/help/views-and-panels) pop-up that appears when you select the `Edit` option from the single record actions menu on the channels list view page:

![Editing popup](../../_assets/channels/channel-editing-popup.jpg)

## Removing

To remove the channel record, use the `Remove` option from the actions menu on its detail view page

![Remove1](../../_assets/channels/remove-details.jpg)

or from the single record actions menu on the channels list view page:

![Remove2](../../_assets/channels/remove-list.jpg)

## Duplicating

Use the `Duplicate` option from the actions menu to go to the channel creation page and get all the values of the last chosen channel record copied in the empty fields of the new channel record to be created. Modifying the channel code is required, as this value has to be unique.

## Working with Products Related to Channels

Products that are linked to the channel are displayed on its detail view page on the `PRODUCTS` panel and include the following table columns:
 - Name
 - SKU
 - Type
 - Active

![Channel products](../../_assets/channels/channel-products.jpg)

To create a new product from this view, use the `+` button located on the `PRODUCTS` panel and enter the necessary data in the product creation pop-up that appears:

![Creating products](../../_assets/channels/channels-create-product.jpg)

To link the already existing products with the given channel, use the `Select` option from the actions menu located in the upper right corner of the `PRODUCTS` panel. Then in the "Products" pop-up window choose one or several products you would like to assign to this channel and click the `Select` button.

To see all products linked to the given channel, use the `Show full list` option:

![Channel products](../../_assets/channels/show-full-option.jpg)

Then the "Products" page opens, where all product records [filtered](https://treopim.com/help/search-and-filtering) by the given channel are displayed:

![Products full list](../../_assets/channels/products-full-list.jpg)

To view the channel related product, click its name in the products list or select the `View` option from the single record actions menu for the appropriate record:

![View product](../../_assets/channels/products-view.jpg)

To edit the product, use the `Edit` option from the single record actions menu for the appropriate record. In the editing pop-up window that appears make changes in the desired fields, where possible. Click the `Save` button to apply your changes.

Use the `Unlink` option from the single record actions menu to unlink the desired record from the channel and confirm your decision in the pop-up that appears:

![Unlink confirmation](../../_assets/channels/unlink_confirmation.jpg)

To remove the product, select the `Remove` option from the single record actions drop-down list for the appropriate record.

*Please, note that the **"Pricing"** module greatly extends the channels functionality. To learn more about the module and its features, please, visit our [store](https://treopim.com/store/pricing).*