# Cherry Shortcodes
A pack of WordPress shortcodes.
Сompatibility: Cherry Framework v.4+

##Change log##

#### v1.0.5 ####

* NEW: Attribute in `box` and `box_inner` shortcode - background-size
* UPD: Compressed css/js
* UPD: Set of default attributes in `posts` shortcode
* FIX: Correctly get image URL for image icon in `list` shortcode
* ADD: `get_image_url` static method to shortcode tools

#### v1.0.4 ####

* FIX: Updater class logic
* FIX: `video_preview` shortcode
* FIX: WP 4.3.0 compatibility - updated constructor method for WP_Widget
* FIX: image size attribute for a `banner` shortcode
* FIX: default attributes value for `col` shortcode - offset, pull, push
* UPD: Font Awesome to 4.4.0

#### v1.0.3 ####

* UPD: Optimize a shortcode registration
* UPD: Shortcode descriptions
* UPD: Element with type `upload` (added a new attribute - `data_type`)
* FIX: Dependence plugin

#### v1.0.2 ####

* FIX: https://github.com/CherryFramework/cherry-shortcodes/issues/1
* FIX: returned filters
* FIX: `crop_image` function
* UPD: raname .pot file

#### v1.0.1 ####

* ADD: `[video_preview]` shortcode
* ADD: `lightbox_image` attribute for `[posts]` shortcode
* ADD: callback for `lightbox` macros
* ADD: a filter for tab style selector
* ADD: a landing page functional
* UPD: callback-functions
* UPD: waypoint.js
* UPD: parallax.js
* FIX: type in `[counter]` shortcode