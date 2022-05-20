<!---
Full module name and description.
-->
# farm_species
Species taxonomy for farmOS .

This module is an add-on for the [farmOS](http://drupal.org/project/farm)
distribution.


<!---
Geting started.
-->
## Getting started

<!---
Document installation steps.
-->
### Installation

Install as you would normally install a contributed drupal module.

See: https://www.drupal.org/docs/extending-drupal/installing-modules for further information.

<!---
Document any special configuration the module requires. For example:
- API Keys
- Additional settings options
- External (client) configuration
-->
### Configuration

There's no need of additional configuration

<!---
Document features the module provides.
-->
## Features

Provides a species taxonomy

### Taxonomies

Creates a new taxonomy:

#### species

This taxonomy has some extra fields:
- `scientific_name` (string): The scientific name of the species.
- `image` (image): A image field

The module also extends all asset-related taxonomies:

#### plant_type

Add species field and hide crop_family

#### animal_type

Add species field

#### material_type

Add species field

<!---
Document any quick forms provided by this module.
-->
### Quick Forms

<!---
It might be nice to include a FAQ.
-->
## FAQ

Does this module remove the crop_family taxonomy? NO. It hides the field on the plant_type form view

<!---
Include maintainers.
-->
## Maintainers

Current maintainers:
* Hadrián Candela (c4ndel4) - https://github.com/c4ndel4
