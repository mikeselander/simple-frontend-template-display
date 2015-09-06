Simple Frontend Template Display
================================

#### Adds an admin toolbar menu item that displays the current page template.

Simple Frontend Template Display will show the name of the template that you’re using in the toolbar when you’re in the frontend of your website. You can use this to keep track of the various templates you’re using without having to hop into the edit screen every time you want to check a template.

All you have to do to get this working is to install the plugin. It will then automatically show up in the toolbar on all pages on your site. 

I hope this speeds up your development work!

#### Usage 

1. Upload `Simple Frontend Template Display` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the `Plugins` menu in WordPress
3. Magic! On your pages, the name of the template will show on the toolbar on the frontend

#### Changelog 

= 0.3.1 =
* Fixed Strict PHP standards error concerning line 184
* Tested up to 4.0

= 0.3.0 =
* Added get_similar_pages function to retrieve pages with the same template

= 0.2.0 =
* Added a drop down with the filename so you can see all of the template data
* Changed add_menu method to the preferred add_node
* Split up the filename and template name functions to allow for the separate dropdown
* Fixed several typographical & commenting errors

= 0.1.0 =
* Initial release