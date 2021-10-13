=== Plugin Name ===
Contributors: (this should be a list of wordpress.org userid's)
Donate link: https://paypal.me/imobsphere?locale.x=en_GB
Tags: custom post type slug, remove custom post type slug, slug, post type, clean url
Requires at least: 3.0.1
Tested up to: 5.8.1
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin will help you to remove the default custom slug of post type from the url which is common requirement for all the SEO lovers.

With less technical knowledge you can have this feature into the place.

== Description ==

This plugin will give you the advantage of having the clean seo url. You can remove custom post type  slug and have the seo friend url by click couple of clicks. 

This plugin can remove the custom custom post type  slug as well by going into the plugin settings. 

You can do this by doing the admin login and check admin menu > Remove custom post type  Slug Settings

Once you click on it you will be able to see all existing the custom post type  slug you just need to selected it and save the settings. 

For the developer i have given the filter as well with the use of that filter you can directly add the slug in the array which will remove the slug. 

Filter name is remove_custom_post_type_slug.
add_filter( 'remove_custom_post_type_slug',function ( $slug_list ){
	return $slug_list
} )

In the above array you need to make sure that you pass the slug name as it is. 

It is working with the below functions you just need to make sure that you have used the one of the below function to have the post link.

post_type_link
get_the_permalink
the_permalink

This plugin is compatible with custom post type ui as well.

Apart of this you can create the ticket for your query or reach me out for quick question on akshay.shah5189@gmail.com

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload `remove-post-type-slug.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `<?php do_action('plugin_name_hook'); ?>` in your templates


== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the /assets directory or the directory that contains the stable readme.txt (tags or trunk). Screenshots in the /assets
directory take precedence. For example, `/assets/screenshot-1.png` would win over `/tags/4.3/screenshot-1.png`
(or jpg, jpeg, gif).
2. This is the second screen shot

== Changelog ==

= 1.0 =
* A change since the previous version.
* Another change.
