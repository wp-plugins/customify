=== Customify - A Theme Customizer Booster ===
Contributors: pixelgrade, euthelup, babbardel
Tags: customizer, css, editor, live, preview, customise
Requires at least: 3.8.0
Tested up to: 4.2.1
Stable tag: 1.1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Customify is a Theme Customizer Booster that you can easily use to add Fonts, Colors, Live CSS Editor and other options to your theme.

== Description ==

With [Customify](https://github.com/pixelgrade/customify), developers can easily create **advanced theme-specific options** inside the WordPress Customizer. Using those options, a user can make presentational changes without having to know or edit the theme code.

**Types of Fields**

* **Color.** A color picker used to control any text or background color of an element.

* **Typography.** A series of typographic options that allow you to access the massive **Google Fonts library** and make them available inside your theme customizer.

* **CSS Editor.** A powerful **Live CSS Editor** directly into your customizer! Useful for better control over the appearance of your theme without the need to create a child theme or worry about theme updates overwriting your customizations.

* **Text Field.** A simple text field that allows you to customize elements like Site Title or Footer Credits.

* **Select Dropdown.** A drop-down menu selector to be used when you have to choose from multiple options.

* **Range.** The html5 range element can be used to select number values.

* **[Preset](https://github.com/pixelgrade/customify/blob/master/README.md#presets_title).** A field which allows you to change a group of Customify fields.

== Changelog ==

= 1.1.2 =
* Added: Option to add Customify's changes in the editor.
* Added: Possibility to load Typekit fonts through config.

= 1.1.1 =
* Added: Radio input with image label.
* Added: Javascript callback for css properties.
* Update: Updated Ace editor.

= 1.1.0 =
* Added: [Preset](https://github.com/pixelgrade/customify/blob/master/README.md#presets_title) field type.
* Added: Reset buttons (disabled by default).
* Added: Button field.

== Installation ==

1. Install Customify either via the WordPress.org plugin directory, or by uploading the files to your `/wp-content/plugins/` directory
2. After activating Customify go to `Appearance → Customize` and have fun with the new felds
3. For further instructions and how to setup your own fields, read our [detailed documentation](http://github.com/pixelgrade/customify/blob/dev/README.md)

== Frequently Asked Questions ==

= Is there a way to reset Customify to defaults? =
Reset buttons are available for all the options or for individual sections or panels.
They are disabled by default to avoid useless/accidental resets.
To enable them simply go to Dashboard -> Settings -> Customify and check "Enable Reset Buttons"
