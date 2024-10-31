=== Responsive Divi Backgrounds ===
	Contributors: emandiev
	Tags:  Divi, Divi Theme, Divi Optimization, Responsive Images
	Requires PHP: 5.0
	Stable tag: 1.0.2
	Requires at least: 4.1
	Tested up to: 5.3
	License: GPLv3 or later
	License URI: https://www.gnu.org/licenses/gpl-3.0.html

	Serve properly sized backgrounds to your visitors and boost your website performance! This plugin works only with the Divi Builder.

== Description ==

"Responsive Divi Backgrounds" will allow you to optimize your website's image delivery.<br />
This plugin works only with the <a href="https://www.elegantthemes.com/plugins/divi-builder/">Divi Builder</a>, usually part of the Divi Theme.<br />
No configuration required.<br />

== Installation ==

1. Visit <strong>Plugins > Add New</strong>
2. Search for "<strong>Responsive Divi Backgrounds</strong>"
3. Download and Activate the plugin.

== Frequently Asked Questions ==

= What are the requirements? =

The Divi Builder by Elegant Themes.

= What are responsive backgrounds and why should I care? =

When you upload any image into your website, WordPress automatically creates several smaller variants of your image.
If you display the image in a <img> tag, the visitor will load a size that's appropriate to their device.

This is a great way to speed-up your website and save bandwidth.
However, WordPress doesn't handle background images in this way.

By default, the Divi Builder will always show full-sized background images.
This isn't great because mobile users will have to download an unnecessary big file.

Especially for sliders, you would probably upload an image with size of atleast 1920x1080px to make it look good on big displays.
But what if your visitor is using a 320x640px phone?
They don't need the big image, right?

This is where the "Responsive Divi Backgrounds" plugin comes in handy.
The plugin prints CSS in the footer on pages that have slides or sections with background images.
The CSS basically tells the browser to display small-sized images on small devices, medium-sized images on bigger devices and so on.

Still don't think you need this?
Just run a Google PageSpeed Insights test and you will see the "Properly size images" opportunity lowering your score.

= What about browser support? =

All browsers are supported (back to Internet Explorer 9).
The plugin will simply print some <a href="https://caniuse.com/#feat=css-mediaqueries">CSS media queries</a> in the footer.

= Will this plugin affect the performance in a bad way? =

The plugin should not cause any noticeable slowdown.
It's designed to help improve your website's performance.
The plugin won't load any additional files.
Instead, it simply prints CSS inline in the footer.

The plugin checks the current page's content and if there is a slider or a section with a background image, then the CSS gets printed.
All other posts/pages won't be affected to maximize performance.

= Any other recommendations for my Divi website? =

Yes! Try out my lazy loading plugins to further improve your performance and PageSpeed Insights score.
<a href="https://wordpress.org/plugins/lazy-load-divi-slider-backgrounds/">Lazy Load Divi Slider Backgrounds</a>
<a href="https://wordpress.org/plugins/lazy-load-divi-section-backgrounds/">Lazy Load Divi Section Backgrounds</a>

== Changelog ==

= 1.0.0 =
Release date: 15/12/2018
- Initial release

= 1.0.1 =
Release date: 14/01/2019
- Small fix to stop the "Undefined index" PHP Notice

= 1.0.2 =
Release date: 13/09/2019
- Fix PHP Notice in admin dashboard. Main plugin logic will now load only on front-end.
- SVG images will now be skipped instead of causing errors.
- Improve code readability.