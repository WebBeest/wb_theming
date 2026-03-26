# Web-Beest - Theming
This recipe is designed to configure a list of modules and configuration needed
for theming in a Drupal site.

## Features
Adds and configures the following modules:
* [Storybook](https://drupal.org/project/storybook)
* [Styleguide](https://drupal.org/project/styleguide)

For the Storybook module:
- The permission 'render storybook stories' is granted to anonymous in this
recipe. Please disable it in production.
- Please refer to the Storybook module page for further configuration, like
CORS settings, Yarn and StorybookJS installation.
