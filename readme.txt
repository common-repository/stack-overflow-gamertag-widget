=== Stack Overflow "GamerTag" Style Reputation Widget ===
Contributors: grumpydev
Donate link: 
Tags: stack overflow, stackoverflow, widget, sidebar
Requires at least: 2.7
Tested up to: 2.7
Stable tag: trunk

XBox Live "GamerTag" style widget for displaying your Stack Overflow rep.

== Description ==

XBox Live "GamerTag" style widget for displaying your [Stack Overflow](http://stackoverflow.com/ "Visit Stack Overflow") 
information. Currently displays:

* Name
* Gravatar
* Reputation
* Badges

It also links to your profile screen.

As from 2.0.0 the widget now uses the Stack Overflow JSON feed, rather than a screen scrape. 
This means that json_decode must be available (i.e. PHP5>=5.2.0). If you can't satisfy that
requirement then you should stick with 1.0.4.

Changelog:
1.0.4 - Added caching, configurable in the settings, defaults to 30minutes.
2.0.0 - Switched from screen scraping to decoding the SO JSON feed.

== Installation ==

1. Upzip to the wp-content/plugins/ directory.
1. Activate using the plugins menu in Wordpress
1. Add the widget from the widget menu in Wordpress
1. Add your user id and email address in the configuration on the right side of the widget menu

== Frequently Asked Questions ==

= How do I get my user id? =
Log into Stack Overflow, click your name at the top and your id is the number
just after /users/ e.g. if your url was http://stackoverflow.com/users/12345 then 12345 is the
user id.

= Why do you need my email address? =
The email address is hashed and used for your Gravatar. It isn't used for anything else
or stored for any evil purposes.

== Screenshots ==
1. Screenshot


