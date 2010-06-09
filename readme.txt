=== Plugin Name ===
Contributors: Benoit Gilloz
Tags: flickr, photostream, flickr photostream, flickr widget
Requires at least: 2.8
Tested up to: 3.0-alpha
Stable tag: trunk

Simple Flickr Photostream widget allow you display pictures from Flickr in a widgetized area of you choice. Based on the WP 2.7 widget model

== Description ==

Simple Flickr Photostream widget is another Flickr photo display. I exists because no other plugins were doing what the author needed.

The plugin is essentially a widget that will show picture from a chosen Flickr source, be it your own photostream, someone else's, one of your sets, a group, your favorite, etc...

The code is based on [FlickrRss](http://eightface.com/wordpress/flickrrss/) plugin made by Dave Kellam and Stefano Verna and improves by placing the controls in the widget itself rather than an admin page. This new approach, combined with the way WP 2.7 handles widgets makes it multiwidgets enabled with different options for each widgets.

Note: plugin provided as is. I will not take any responsability if anything breaks. Backup backup backup...

Note2: If you are using the cache function do not forget to clean up every so often. Cached pictures are not deleted automatically (yet) so you may find quite a few of them in you upload folder after a while.

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload `simple-flickr-photostream-widget.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go the widget page and drag the "Simple Flickr Photostream" widget in your sidebar area.


== Changelog ==

= 1.1 =
* Fix a bug in source dropdown. When a user was selecting a source for the first time, before saving the widget, some input fields where not hiding correctly. 

= 1.0 =
* First release
