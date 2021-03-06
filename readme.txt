=== Plugin Name ===
Contributors: george_michael
Donate link: 
Tags: 
Requires at least: 3.5.2
Tested up to: 4.6.1
Stable tag: 1.0.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Allows users to receive an email if a post is updated.

== Description ==

This plugin puts a "Subscribe" button to the bottom of posts so users can be notified when a post changes. Subscribed users will get an email that contains a link to the post. If they wish to no longer receive email notifications, the button at the bottom of the post will unsubscribe them.

== Installation ==

1. Upload `post-delta-notification.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Does it work with pages and/or custom post types? =

It works with pages and posts and should work with custom types as well, though I haven't tried.

== Screenshots ==

1. The main settings page.
2. A subscribe button at the bottom of a post.

== Changelog ==

= 1.0.4 =
* Works properly with pages as well as posts now.

= 1.0.3 =
* Removed PHP4 constructor from class as WP 4.3 deprecated that type of constructor.

= 1.0.2 =
* Fixed an error that would show up in logs.

= 1.0.1 =
* Fixed subscribe/unsubscribe bug to work with WP 4.0

= 1.0.0 =
* Initial version.

== Upgrade Notice ==

= 1.0.4 =
* Bug fix for working with pages. If you have a lot of pages, take note that you will likely want to add them to the list of excluded page/post ids in the options page.

= 1.0.3 =
* Required upgrade if using WP 4.3.

= 1.0.2 =
* Bug fix. Upgrade recommended.

= 1.0.1 =
* If you are running WP 4.0, you will need to upgrade.