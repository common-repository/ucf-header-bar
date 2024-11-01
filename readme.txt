=== UCF Header Bar ===
Contributors: jhendricker
Donate link: 
Tags: ucf, header bar
Requires at least: 3.9
Tested up to: 6.5.4
Stable tag: 1.05
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add the UCF Header bar into any WordPress website. Recommended for use on all UCF WordPress websites.

== Description ==

The UCF Header Bar plugin allows the simple inclusion of the [UCF Header bar](https://universityheader.ucf.edu/) into your UCF WordPress website using enqueue_script.  The UCF University Header is a cohesive marketing and branding tool for the entire university. It provides consistent navigational elements and a universal search feature with search suggestions.

The University Header has a responsive option and will adapt to various screen sizes as necessary. Responsiveness follows Twitter Bootstrap's breakpoint standards.

== Installation ==

Installation is quick and easy with only one setting.

1. Upload the plugin files to the `/wp-content/plugins/ucf-header-bar` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Use the Settings->UCF Header Bar screen to configure the plugin if your site's max-width is larger than 1200px.

== Frequently Asked Questions ==

= Where will the UCF Header Bar be added? =

The UCF Header Bar should be visible at the top of your website right after the opening `<body>` tag.

= Are there any settings? =

For sites with a max-width greater than or equal to 1200px please go to the plugin settings found under Settings->UCF Header Bar and check the box.

= Why isn't the UCF Header Bar acting responsively? =

To utilize a responsive bar, simple make sure your sites `<head` includes the following `<meta>` tag:

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`

= Are there any known issues with themes? =

There are some themes that have sticky headers that can conflict with the UCF Header Bar implementation.  If your theme has a sticky header, please test its functionality after activating the UCF Header Bar plugin.

== Screenshots ==

1. screenshot-1.jpg
2. screenshot-2.png

== Changelog ==

= 1.05 =
* Due to changes in the parent JavaScript a new CSS file is enqueued if the settings are set to greater than or equal to 1200px.
* Updated the main screenshot.
* Tested on WordPress 6.5.4

= 1.04 =
* Prefixed functions and class to prevent potential function naming clashes.
* Tested on WordPress 4.9.4

= 1.03 =
* Fixed another typo

= 1.02 =
* Fixed a typo

= 1.01 =
* Removed duplicate "Settings Saved" announcement

= 1.0 =
* Initial plugin submission.
* Tested on WordPress 4.4.2.