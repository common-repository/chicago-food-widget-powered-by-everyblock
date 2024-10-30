=== Plugin Name ===
Contributors: avenger339, Everyblock
Tags: widgets, everyblock, widget, food, chicago, illinois, inspections, food inspections, food inspection, inspection
Tested up to: 3.6.1
Requires at least: 3.6.1
Stable tag: 2.0.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add a Chicago Food Widget Powered by Everyblock to a post or page.  Will also allow you to add as a widget.

== Description ==

Add a Chicago Food Widget Powered by Everyblock to a post or page.  Will also allow you to add as a widget.

== Installation ==

1. Add the folder to wp-content/plugins.
2. On the plugins page in the dashboard, click the "Activate" button under "Chicago Food Widget Powered by Everyblock".
3. On the dashboard, hover over "Plugins", and click on "Everyblock API Key".
4. Enter in your Everyblock API Key and press "Update API Key".
5. If you want to embed in a post, use the shortcode [display_chicago_food_widget].  This will add a 300x500 widget.  You can specify sizes by adding the attributes width and height (example: [display_chicago_food_widget width=400 height=600]).
6. If you want to add as a widget, drag the widget labeled "Chicago Food Inspections Widget" to the appropriate location.  You can change the height or width.

== Screenshots ==
1. The food widget added to a page.

== Frequently Asked Questions ==

= How do I get an Everyblock API Key? =

If you've already entered an API key for other Everyblock widgets, then you do not need to do this again.  One key will work for all everyblock widgets.

First, you will need an Everyblock Account.

Navigate your browser window to https://chicago.everyblock.com/account/register/.  Select a username and password, and enter your zip code.

Next, navigate to http://www.everyblock.com/developers/.  Click "Create Developer Profile".  Enter your First Name, Last Name, and if applicable, your company or organization.  Next, click "Create New Project".  Enter a Project Name, the URL to your site, and a brief description.  Next, click "Save Project".  Click "Create Key".  A new API key will generate.  Enter this key in the Wordpress Dashboard, under Plugins -> Everyblock API Key.

= Why are no entries or neighborhoods loading in my widget? =

First, make sure you set an API Key in Plugins -> Everyblock API Key.  Second, make sure the API Key is valid.  If it is still not working, please check the current running status of the Everyblock API.

= How do I add the food inspections widget to a post or page? =

After activating the plugin, add the shortcode [display_chicago_food_widget] to any page or post.  

= How do I change the width and height of the widget while it is embedded in a page or post? =

Add the shortcode attributes width and height.  Example: [display_chicago_food_widget width=400 height=600].

= How do I add the food inspections widget to a sidebar, header, or footer? =

After activating the plugin, go to Appearance -> Settings, and drag the "Chicago Food Inspections Widget" to the appropriate area. 

== Changelog ==

= 1.0 =
* First release.

= 1.0 =
* Updated to use the Everyblock API.
* Added the ability to add widgets to a sidebar, header, or footer.
* Added the ability to change the width and height.

== Upgrade Notice ==

= 1.0 =
* First Release

= 2.0 =
* Updated to use the Everyblock API.
* Added the ability to add widgets to a sidebar, header, or footer.
* Added the ability to change the width and height.

= 2.0.2 =
* Changed shortcode to [display_chicago_food_widget].

= 2.0.3 =
* Fixed bug with the date on the widget.