---
menuTitle: displayAdditionalCustomerAddressFields
Title: displayAdditionalCustomerAddressFields
hidden: true
hookTitle: Display additional customer address fields
files:
  - Classic Theme: templates/customer/_partials/block-address.tpl
locations:
  - front office
type: display
hookAliases:
origin: theme
---

# Hook displayAdditionalCustomerAddressFields

## Information

{{% notice tip %}}
**Display additional customer address fields:** 

This hook allows to display extra field values added in an address form using hook 'additionalCustomerAddressFields'
{{% /notice %}}

Hook locations: 
  - front office

Hook type: display

Hook origin: theme

Located in: 
  - [Classic Theme: templates/customer/_partials/block-address.tpl](https://github.com/PrestaShop/classic-theme/blob/develop/templates/customer/_partials/block-address.tpl)

## Call of the Hook in the origin file

```php
{hook h='displayAdditionalCustomerAddressFields' address=$address}
```