# Enable / Disable Multiple Products
Extensions for OpenCart 1.5.x

**What:** adds multi-product "Enable" and "Disable" functionality to Product List on Admin Dashboard to update the status of one or more products at a time. Clears cache on update so results show up instantly on website front-end.

**Where:** two new buttons, "Enable" and "Disable" are added next to the default "Insert", "Copy", and "Delete".

**How:** works differently than currently existing available ajax extensions, which only allow a change of the product status by clicking a single product at a time. This extension makes use of the checkboxes to select multiple products (or all) and executes upon clicking the appropriate new button.

**More:** displays a success message indicating the number of products enabled/disabled and updates the system cache so that changes take effect instantly on the website front-end.

Requirements: OpenCart v1.5.4-1.5.6 with vQmod installed

## CHANGELOG

v1.0.1
-------
- added cache refresh on update so results show up instantly on website front-end

