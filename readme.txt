=== jonradio Current Year and Copyright Shortcodes ===
Contributors: jonradio
Donate link: http://jonradio.com/plugins
Tags: copyright, date, year, shortcode, plugin
Requires at least: 3.0
Tested up to: 3.8
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Provides Shortcodes to display the Current Year and/or a Copyright symbol.

== Description ==

Inserts the current Year into a Post or Page through the use of a Shortcode.  And always keeps it up to date.  For example, a Page created today (2014) viewed 5 years from now (2019) will show the Year current when it is viewed (2019) by any site visitor.

A second Shortcode inserts a Copyright symbol:  &copy;.  And a third provides both because of WordPress restrictions of using two Shortcodes side-by-side.

The `[y]` shortcode inserts the four digit current year into any Page or Post no matter whether you use the Visual or the HMTL editor tab in Edit Post or Edit Page.  The `[c]` shortcode inserts the &copy; Copyright symbol, using the official HTML coding for a copyright symbol.  The `[cy]` shortcode inserts the &copy; Copyright symbol, a blank and the current year.

For example, if you are continually refining an older article that you want to copyright on a WordPress Page, you could put the following at the bottom of the page:
`[c] 1997-[y] John Smith`
Assuming it is currently the year 2014, that would display as:

&copy; 1997-2014 John Smith

In 2015, it would automatically display as &copy; 1997-2015 John Smith without anyone having to edit the Page.

IMPORTANT USAGE NOTE:  Older versions of WordPress did not support the use of two Shortcodes in a row on a Page or Post.  In other words, `[c][y]` did not write.  That is why the `[cy]` Shortcode has been provided.

== Installation ==

This section describes how to install the *jonradio Current Year and Copyright Shortcodes* plugin and get it working.

1. Use **Add Plugin** within the WordPress Admin panel to download and install this *jonradio Current Year and Copyright Shortcodes* plugin from the WordPress.org plugin repository (preferred method).  Or download and unzip this plugin, then upload the `/jonradio-current-year-and-copyright-shortcodes/` directory to your WordPress web site's `/wp-content/plugins/` directory.
1. Activate the *jonradio Current Year and Copyright Shortcodes* plugin through the **Installed Plugins** Admin panel in WordPress.  If you have a WordPress Network ("Multisite"), you can either **Network Activate** this plugin, or Activate it individually on the sites where you wish to use it.  Activating on individual sites within a Network avoids some of the confusion created by WordPress' hiding of Network Activated plugins on the Plugin menu of individual sites.  Alternatively, to avoid this confusion, you can install the *jonradio Reveal Network Activated Plugins* plugin.
1. Insert the `[y]`, `[c]` and/or `[cy]` shortcodes as many times as you wish in one or more WordPress Pages or Posts; note the current WordPress restriction that no two Shortcodes cannot be placed *side by side*, i.e. - `[c][y]` will not work.

== Frequently Asked Questions ==

= Why are some or all of the Shortcodes showing instead of their values being displayed? =

This can happen if this plugin is not activated on the site you are using it on.  It can also happen if you use two shortcodes without any other text in between.  This is a longtime WordPress restriction -- side by side shortcodes do not work correctly -- that will be resolved in a Future Release of WordPress.

= How can I change the names of the Shortcodes? =

If there is enough interest, we will add that capability to a future version.  Please let us know, including your ideas on how you would like it to work, and any shortcode naming conflicts with other plugins that you found.

== Screenshots ==

1. `[c] 1997-[y] John Smith` as it would be displayed in the year 2012

== Changelog ==

= 1.0 =
* Copyright shortcode added
* Current Year Shortcode converted from Shortcode Exec PHP plugin to standalone Plugin

== Upgrade Notice ==

= 1.0 =
Production version, updated to meet WordPress Repository standards