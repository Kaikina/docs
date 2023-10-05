---
menuTitle: displayContactRightColumn
Title: displayContactRightColumn
hidden: true
hookTitle: Right column blocks of the contact page
files:
  - Hummingbird Theme: templates/contact.tpl
  - Classic Theme: templates/contact.tpl
locations:
  - front office
type: display
hookAliases:
origin: theme
---

# Hook displayContactRightColumn {{< minver v="8.1" >}}

## Information

{{% notice tip %}}
**Right column blocks of the contact page:** 

This hook displays new elements in the right-hand column of the contact page.
This replaces widget `ps_contactinfo` on hook `displayRightColumn`.
{{% /notice %}}

Hook locations: 
  - front office

Hook type: display

Hook origin: theme

Located in: 
  - [Hummingbird Theme: templates/contact.tpl](https://github.com/PrestaShop/hummingbird/blob/develop/templates/contact.tpl)
  - [Classic Theme: templates/contact.tpl](https://github.com/PrestaShop/classic-theme/blob/develop/templates/contact.tpl)

## Call of the Hook in the origin file

```php
{hook h='displayContactRightColumn'}
```