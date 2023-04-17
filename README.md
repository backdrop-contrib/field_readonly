Field Readonly displays non-accessible fields in edit forms as read-only items.

Modules like the essential [Field Permissions](https://backdropcms.org/project/field_permissions) allow to make fields non-accessible by completely hiding them in edit forms even if user has the permission to view them.

Field Readonly lets you display these fields back in edit forms, rendered the same way as in view mode.

## Features
- Acts on any non-accessible Field API field (made non-accessible by the use of the Field Permissions module or other)
- Works with any entity type
- Works with any widget
- Adds a new Field Readonly view mode that lets you control separately the way your read-only fields should be displayed in forms
- Very tiny!

## Instructions
1. Install [Field Permissions](https://backdropcms.org/project/field_permissions)
2. In the Manage fields tab for your node (or other entities), click on Manage for the field you want to show as "read only", scroll down to the Global settings fieldset, and select "Custom permissions"
3. Be sure to select both "View" permissions for the role you want to see the field as read-only
4. Log in as a user with that role and go to the node edit form 

Just make sure that your fields are not completely private! User must have the right to view them.
So if you use Field Permissions, check Custom permissions under Field visibility and permissions, then check View own value for field FIELD_NAME or View anyone's value for field FIELD_NAME depending on what you want.

You may use custom display settings for the new Field Readonly view mode only if you want separate control on how your read-only fields should render on edit forms.

## Credits
- This module was developed by [Absyx Development](https://www.drupal.org/node/1765114).
- Current Drupal 7 maintainer: [anrikun](https://www.drupal.org/u/anrikun)
- Ported to Backdrop CMS by [argiepiano](https://github.com/argiepiano)

## Current maintainers
- Maintainer for the Backdrop CMS version: [argiepiano](https://github.com/argiepiano)
- Seeking co-maintainers

## License
This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.