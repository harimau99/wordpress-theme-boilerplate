# WordPress Theme Boilerplate

This package contains Theme Boilerplate, which has a lot of improvements and security patches, according to 
standard WordPress theme boilerplates (like underscore, etc.). The code is object-oriented and works with PSR-4 autoload. 

## Requirements

* PHP 7.0+
* [WordPress Theme Framework](https://github.com/justcoded/wordpress-theme-framework) plugin.

Theme core files (base classes) are presented as separate wordpress plugin package 
called [WordPress Theme Framework](https://github.com/justcoded/wordpress-theme-framework). They were
moved as a plugin to provide easier support and updates population through different site installations.

This solution makes possible to deliver new updates and hot fixes without modifying the theme code.

## What is inside?

### Better file structure
The organization of a theme is very similar to a modern PHP Frameworks. We totally separated registration of hooks and components, query logic and the templates.

We tried to keep as much standard WordPress features as possible, so all "views" works in the same Template
Hierarchy as standard templates, just grouped by a content types (with folders).

![File structure](https://github.com/justcoded/wordpress-theme-boilerplate/wiki/assets/boilerplate-file-structure.png)

### Template Inheritance

We added modern template inheritance system based on layouts (very similar to Laravel and Yii frameworks). 
Some WordPress developers call it a "Theme Wrapper". Markup is handled by one layout file 
(or more if needed) instead of being scattered across all template files like typical themes.
Stay <abbr title="Don't repeat yourself">DRY</abbr>!

## Security and optimizations

Theme files are nice and clean, but Theme Framework has a lot of hooks to make your WordPress more secure,
clean up and optimize final generated HTML.

### Documentation

[Read our Wiki](https://github.com/justcoded/wordpress-theme-boilerplate/wiki) to find out all features.    