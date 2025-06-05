# Placeholder Glossary Drupal Recipe

A recipie that enables a glossary. Glossaries can be created as content and then
referred to on other content like Articles (the default example here), Books, or
any entity type.

## Configuring Drupal for Recipes

See https://www.drupal.org/node/3522189#:~:text=Add%20recipe%20unpacking%20to%20an%20existing%20site

## Installing this recipe

TODO: post to Packagist

`composer require lullabot/placeholder-glossary`

## Applying the recipe

Provided you are using `drupal/core-recipe-unpack`, the recipe will be unpacked
into the recipes directory. To apply the recipe:

`php core/scripts/drupal recipe recipes/placeholder-glossary`
