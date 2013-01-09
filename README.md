drupal-custom-module
====================

Drupal custom modules.
In this repoistory i will store drupal custom modules. This is first time when i am using this github and storing the code for one of my custom module. 

Description
-----------
This module adds a link ("Set as Today") to every view node of article content type to your Drupal site.
"Set as Today" which updates a date field that are already added by in article content type. In this module, we have consider the name of date field is field_date. We will update this date field to 'now(today date)' using an AJAX request. The date field value also get updated in the database as well as on the currently displayed node, without a page load.

Requirements
------------
Drupal 7.x
Date module
Date field should be already added in article content type with name "field_date"

Installation
------------
1. Copy this entire module to the Drupal sites/all/modules directory.

2. Login as an administrator. Enable the module in the "Administer" -> "Modules"

3. View article node if already created or create article node first.
