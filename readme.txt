=== autometa's MENTS ===
Contributors: JorgeAmVF
Donate link: https://quaestio.org/
Tags: shortcode, automation, comment, comment list, list, recent comments, recent
Requires at least: 2.8.0
Tested up to: 4.9.2
Stable Tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

It reproduces comment lists in pages, posts, portfolios or products simply via: `[ments]` and `[recents]`.
== Description ==
 
**autometa's MENTS** is a simple plugin that uses the following shortcodes:

* `[ments]`   = to reproduce all comments;
* `[recents]` = to reproduce recents comments.

**autometa's MENTS** is a standalone component of **[autometa](https://wordpress.org/plugins/autometa/)** shortcodes pack.

== Installation ==

1. Install it from *Dashboard*/*Plugins*/*Add Plugins* or download it to your plugin folder;
2. Activate it from *Dashboard*/*Plugins*/*Installed Plugins*;
3. Write the following shortcodes in text fields: `[ments]`, `[recents]`.

== Frequently Asked Questions ==

= Plugin Features =

**[autometa](https://wordpress.org/plugins/autometa/)** reproduces metadata information automatically via shorcodes in general, **autometa's MENTS** generates comment lists in special.

= How To =

Just write one or more of the following shortcodes inside a text field and between brackets as usual: `[ments]` and/or `[recents]`.

= CSS Style Selectors =

* `#ments`    = `[ments]` ID;
* `#recents`  = `[recents]` ID;
* `.autometa` = **autometa** class.

= PHP Functions Reference =

* [`add_shortcode()`](https://developer.wordpress.org/reference/functions/add_shortcode/)
* [`get_comment_author_link()`](https://developer.wordpress.org/reference/functions/get_comment_author_link/)
* [`get_comment_link()`](https://developer.wordpress.org/reference/functions/get_comment_link/)
* [`get_comments()`](https://developer.wordpress.org/reference/functions/get_comments/)
* [`get_the_title()`](https://developer.wordpress.org/reference/functions/get_the_title/)
* [`Walker`](https://developer.wordpress.org/reference/classes/walker/)
* [`wp_list_comments()`](https://developer.wordpress.org/reference/functions/wp_list_comments/)
