=== PayPal Digital Goods powered by Cleeng ===
Contributors: mtymek, Donald Res
Tags: paypal, paypal digital goods, cleeng, content monetization, micropayment, protect, monetize, money, earn money, social payment
Requires at least: 2.9.2
Tested up to: 3.3,1
Stable tag: 2.2.16
License: New BSD License

The PayPal Digital Goods powered by Cleeng plugin is no longer supported. After May 14th 2014 all transactions made via this plugin won't be processed.

== Description ==

The PayPal Digital Goods powered by Cleeng plugin is no longer supported. After **May 14th 2014** all transactions made via this plugin won't be processed.

Please check <a href="http://cleeng.com/">Cleeng.com</a> and <a href="http://cleeng.com/open">Cleeng.com/open</a> for alternative solutions.

== Installation ==

Installation only takes minutes.

In case you use the build-in download function:

1. In the WP admin, in the menu select "Plugins" and "add new"
2. Search for this plugin and click "Install now" and activate it.
3. Continue with item 3 below

In case you don't use the build-in download function of WordPress:

1. Upload Cleeng For WordPress to your /wp-content/plugins/ directory.
2. Activate it in "Plugins" menu in your WordPress admin.
3. Go to settings and create a publisher account (or re-use one if you have one already)
4. Within the right hand site of your edit pages (blog and pages) the Cleeng widget should appear.
5. Now you are able to protect and charge for your content

Check http://cleeng.com for more information


== Frequently Asked Questions ==

You can find the FAQ on http://cleeng.com/support or read and contribute on the Publisher
Community on http://cleeng.com/forum/publishers/

== Screenshots ==

1. This is how Cleeng layer looks
2. PayPal Digital Goods powered by Cleeng
3. Monetization settings (Admin)

== Changelog ==

= 2.2.15 =
* The PayPal Digital Goods powered by Cleeng plugin phase-out.

= 2.2.15 =
* Updated description

= 2.2.14 =
* Updated ZeroClipBoard to latest version

= 2.2.13 =
* Fixed RSS URL

= 2.2.12 =
* added missing french translations
* adjustments for Cleeng PRO
* added some assertions in JS code

= 2.2.11 =
* improved loading speed of pages with Cleeng items
* removed redundant calls to Cleeng API, improved data validation before it is sent
* verify if user has set default pricing conditions with AJAX request
* small CSS improvements

= 2.2.9 =
* italian translations (by Davide Brioschi)
* increased size of "upgrade accout" popup window
* allowed content prices up to 99.99 USD/EUR/GBP

= 2.2.8 =
* fixed link "Please upgrade your account here"
* updated screenshots 
* version number in now reported in html comment
* small CSS update

= 2.2.6 =
* updated plugin description
* redirect to Cleeng settings with anchor
* bulk protection: protect content after first paragraph
* bulk protection: fixed permalink passed to Cleeng
* bulk protection: fixes in behaviour
* restored "About Cleeng" page in overlay
* updated button logic to reflect new free content view policy
* check if $posts is an array

= 2.2.5 =
* Fixed "activate account" not 
* Fixed notices when WP_DEBUG is set to true

= 2.2.4 =
* subscriptions in PayPal mode

= 2.2.3 =
* fixed bulk protection
* fixed form creating new content (many extra zeros appear in referal rate) 
* update plugin pages
* CSS fixes
* Add subscriptions in paypal-only

= 2.2.2 =
* fixed "register as publisher" from wp-admin
* fixed "site wants to open popup window" warning

= 2.2.1 =
* updated channel file

= 2.2.0 =
* bulk protection of content

= 2.1.6 =
* plugin now uses new JavaScript API
* messages from Cleeng platform (like "you already purchased this content") are show directly on Cleeng layer


= 2.1.5 =
* Improved compatibility with some SEO plugins

= 2.1.4 =
* updated publisher registration URL

= 2.1.3 =
* new layer design

= 2.1.2 =
* fixed CSS in PayPal mode

= 2.1.1 =
* check if another instance of Cleeng For WordPress is already activated
* fixed display problem when user had more plugins that add columns to post list

= 2.1.0 =
* code cleanup, plugin is based on classes now which should make it easier to maintain
* CSS fixes
* new column in post list, indicating if given article is protected
* fixed IE9 compatibility issues
* updated French translation

= 2.0.1 =
* fixed settings link in "Plugins" page

= 2.0 =
* NEW! Combining sales per item with full site subscription: provide access via a daily pass, weekly or monthly subscriptions.
* Improved usability and clarified functionalites

= 1.1.13 =
* customer can log out from settings section now
* currency symbol is displayed next to value in protected content list
* self-hosted paypal button

= 1.1.12 =
* CSS tweaks in "create content" dialog

= 1.1.11 =
* properly display content type on purchase button
* enabled scrollbars in popup window

= 1.1.10 =
* fixed parse error

= 1.1.9 =
* fixed displaying publisher's currency in "edit content" dialog
* increased popup window height to fit new purchase screen

= 1.1.8 =
* CSS updates

= 1.1.7 =
* compatibility with "Wordpress for Joomla!" component
* verbose messages when admin is logged in but plugin can't fetch content info from platform
* allowed descriptions longer than 110 characters (still only first 110 are saved on platform)
* added loading indicator
* fixed compatibility problems with Opera

= 1.1.6 =
* compatibility with WP 3.2RC1
* jQuery cookie is embeded in CleengWidget object to prevent conflict in some cases
* escaped dollar sign in Cleeng layer
* use polling instead of postMessage communication (works better for IE browsers)

= 1.1.5 =
* updated frontend CSS

= 1.1.4 =
* Don't try to render Cleeng layer if tags are broken
* fixed settings page for default options

= 1.1.3 =
* fixed typo

= 1.1.2 =
* fixed admin login

= 1.1.1 =
* improvements in CSS file
* removed call to error_reporting from ajax.php (should help for external plugins generating E_NOTICE)
* "what is Cleeng" link opens in new window
* use window.postMessage to communicate between popup and main window if possible

= 1.1.0 =
* 1.1 official release, including optional Cleeng functionality

= 0.9.1 =
* fixed "headers alrady sent" bug for some configurations

= 0.9.0 =
* initial release
