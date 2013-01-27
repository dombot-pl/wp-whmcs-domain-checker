=== LJM WHMCS Domain Checker ===
Contributors: leejmurphy
Donate link: http://www.leemurphy.co.uk
Tags: whmcs, domain checker
License: GPLv2 or Later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Requires at least: 3
Tested up to: 3.5.1
Stable tag: 1.1

A simple plugin for WordPress that allows you to display the Domain Checker for WHMCS in a nice tidy widget.

== Description ==

This plugin will allow you display the Domain Checker integration code for WHMCS in a nice tidy widget. You MUST have WHMCS installed in order for this plugin to work.


**You can follow this plugin on [Git Hub](https://github.com/leejmurphy/wp-whmcs-domain-checker)**

== Installation ==

1. Upload `ljm-whmcs-domain-checker.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go the widgets section in WordPress and drag the WHMCS Domain Checker widget to your widget area of choice
4. Input the path to your whmcs directory. You can use just the root subfolder, e.g. `/whmcs` or the full url, e.g. `http://www.mysite.com/whmcs`
5. Select whether you would like the form to redirect to the domain availability page or the domain purchase page

== Screenshots ==

1. The widget settings in wp-admin
2. The form displayed on the front end within a widget, ready for styling!

== Changelog ==

= 1.1 =
* New: Added screenshots
* New: Added meaningful error messages for incorrect widget configuration
* New: Markdown Readme for Github
* Fix: Set the WHMCS path as either a subfolder or full domain

= 1.0 =
* Created initial version
