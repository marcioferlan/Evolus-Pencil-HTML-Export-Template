# Evolus-Pencil-HTML-Export-Template
==================================

An Evolus Pencil (http://pencil.evolus.vn/) HTML Export Template developed to simplify the viewing of your finished wireframes.

It mimics a bit the functionality of the first version if Axure html formats and uses jQuery (albeit, an old version - 1.3.2).

#### Features
 * View content 1 page at a time. 
 * Side navigation for pages in the left. 
 * Bottom bar for page notes always visible

#### Based on
 * jQuery template by Maxime Delorme
 * Prototype template by Rudy Lattae

# Instructions

## Installation and usage
 * Download the template at https://github.com/marcioferlan/Evolus-Pencil-HTML-Export-Template/raw/master/bin/Pencil_HTML_Export_Template.zip
 * Open Pencil and go to menu ```Tools``` > ```Manage Export Templates...```
 * Click the button ```Install new template...```
 * Select the file ```Pencil_HTML_Export_Template.zip``` you've have just downloaded

## Update and build
 * Download or clone this repo
 * Make your changes to the template files (```StyleSheet.xslt```, ```Resources/main.js```, etc)
 * Run ```./bin/dist.sh```
 * Open Pencil and go to menu ```Tools``` > ```Manage Export Templates...```
 * Click the trash icon to uninstall the previous version
 * Follow the instructions on the ```Installation and usage```, but select the newly generated zip file instead.

## License
 * MIT