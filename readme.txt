=== BP User Information ===
Contributors: beatrizlima
Tags: user, users, members, information
Requires at least: 4.6
Tested up to: 4.7
Stable tag: 4.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Show the information of your users according to your choice in members page.

== Description ==

Select which fields of yours users profile you wanna show in your members page.

== Installation ==

1. Upload the plugin files to the '/wp-content/plugins/plugin-name' directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Use the Settings->User Information screen to configure the plugin.
4. Inside 'wp-content/plugins/buddypress/bp-themes/bp-default/members/members-loop' add the following in line 48 '<?php do_action( 'show_user_data' ); ?>'. If you´re using buddypress default theme put it in 'wp-content/themes/bp-default-master/members/members-loop'.