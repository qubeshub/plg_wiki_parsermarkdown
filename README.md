# plg_wiki_parsermarkdown

Markdown parser for the HUBzero wiki component. This employs the Markdown parser by Carsten Brandt https://github.com/cebe/markdown

## What is Markdown?

Markdown was initially created by John Gruber (of Daring Fireball) as a simple way for non-programming types to write in an easy-to-read format that could be converted directly into HTML.

It uses a very simple formatting syntax to accomplish the same thing that HTML or Rich Text Formatting does.

## What is HUBzero?

HUBzero is an open source software platform for building powerful Web sites that support scientific discovery, learning, and collaboration. Some refer to such web sites as "collaboratories" supporting "team science." We call them "hubs" because each site becomes a focal point for its user community. The HUBzero platform now supports dozens of hubs across a variety of disciplines, including cancer research, pharmaceuticals, biofuels, microelectromechanical systems, climate modeling, water quality, volcanology, and more.

For more information about HUBzero, visit https://hubzero.org.

## Installation

* PHP 5.4+
* HUBzero 2.1.2+

Place these files into a directory called `{HUB WEBROOT}/app/plugins/wiki/parsermarkdown` of your HUBzero install. Move the migration file into the `{HUB WEBROOT}/app/migrations` directory. Run migrations: `php muse migration -f`. This will install the necessary database entry for the CMS to become of aware of and load the plugin. Next, the plugin must be enabled via the Administrative Plugin Manager interface of your hub. Remember to disable any other wiki parser plugins!
