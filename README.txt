=== Ajax Load More for Advanced Custom Fields ===

Contributors: dcooney, connekthq
Author: Darren Cooney
Author URI: https://connekthq.com/
Plugin URI: https://connekthq.com/ajax-load-more/extensions/advanced-custom-fields/
Donate link: https://connekthq.com/donate/
Tags: ajax load more, advanced custom fields, acf, repeater field, repeater, relationship field, relationship
Requires at least: 4.0
Tested up to: 4.7.4
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Ajax Load More extension that adds compatibility with various field types for Advanced Custom Fields.

== Description ==

**Ajax Load More for Advanced Custom Fields** provides additional functionality for infinite scrolling Repeater and Relationship field data with Ajax Load More.

Easily access [Repeater](https://www.advancedcustomfields.com/resources/repeater/) or [Relationship](https://www.advancedcustomfields.com/resources/relationship/) custom field data from a page or post and return the results to Ajax Load More for infinite scrolling.

**[View Documentation](https://connekthq.com/plugins/ajax-load-more/extensions/advanced-custom-fields/)**


= Shortcode Parameters =

The following Ajax Load More shortcode parameters are available when the Advanced Custom Fields extension is activated.

*   **acf** - Enable compatibility with Advanced Custom Fields. (true/false)
*   **acf_post_id** - The ID of the current page/post. Default = $post->ID
*   **acf_field_type** - The type of ACF field. (relationship/repeater)
*   **acf_field_name** - The name of the ACF field.

= Example Shortcode =

    [ajax_load_more repeater="default" acf="true" acf_field_type="repeater" acf_field_name="{your_custom_field_name}"]


== Frequently Asked Questions ==

= What version of Ajax Load More is required? =
You must have v3.0+ of Ajax Load More installed.

= How do I use this extension? =
Once installed, visit the Ajax Load More Shortcode Builder and build a custom shortcode specifying the ACF field type (acf_field_type) and field name (acf_field_name). 

= What field types of Advanced Custom Fields are supported? =
Repeater and Relationship fields are currently supported.

= How do I infinite scroll Repeater fields with Ajax Load More =
Create an [ajax_load_more] shortcode and set the acf_field_type to repeater.

= How do I infinite scroll Relationship fields with Ajax Load More =
Create an [ajax_load_more] shortcode and set the acf_field_type to relationship.


== Screenshots ==



== Installation ==

= Uploading in WordPress Dashboard =
1. Navigate to the 'Add New' in the plugins dashboard
2. Navigate to the 'Upload' area
3. Select `ajax-load-more-for-acf.zip` from your computer
4. Click 'Install Now'
5. Activate the plugin in the Plugin dashboard

= Using FTP =
1. Download `ajax-load-more-acf.zip`.
2. Extract the `ajax-load-more-for-acf` directory to your computer.
3. Upload the `ajax-load-more-for-acf` directory to the `/wp-content/plugins/` directory.
4. Ensure Ajax Load More is installed prior to activating the plugin.
5. Activate the plugin in the WP plugin dashboard.


== Changelog ==

= 1.0 - May 4, 2017 =
* Initial Release.


== Upgrade Notice ==
* None 