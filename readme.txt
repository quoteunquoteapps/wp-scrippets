=== WP Scrippets ===
Contributors: nyousefi
Tags: screenwriting, scrippets, scrippet, screenplay, film scripts, movie scripts
Requires at least: 1.5
Tested up to: 2.8
Stable tag: 1.5.1

This plugin converts text entered in the Scrippet format to properly styled HTML.

== Description ==

The Scrippet format is a text format designed by John August to allow writers to input screenplay text in easy-to-write plain text and have it converted to properly styled HTML. 

This plugin will automatically convert plain text Scrippet to HTML, and add John August's Scrippets CSS file into your blog. 

For more information on Scrippets please see http://scrippets.org

== Installation ==

1. Download scrippets.zip.
2. Unzip the archive.
3. Upload the entire "wp-scrippets" folder into your "wp-content/plugins" directory.
4. Activate the plugin through the Admin plugins panel.
5. Enjoy!

== Screenshots ==

1. Shows a fully formatted Scrippet using the Drop Shadow border style.


== Usage ==

To include a Scrippet in your WordPress blog simply include text in the following format:

[scrippet]
INT. HOUSE - DAY

MARY yells across the hall to FRANK.

MARY
Anything you want to tell me?

FRANK (O.S.)
I swear, honey, I don't know how mayonnaise got in the piano.

CUT TO:

FRANK

running out of the bathroom.

FRANK
(terrified)
There are bees in the toliet!
[/scrippet]

Note: Scrippet text must be wrapped in [scrippet][/scrippet] blocks, and it must have correct line spaces between screenplay elements.

You can make text bold, italic, or underlined by in the following ways:

= Bold =
* Wrap the text in double asterisks (**bold**) or [b][/b].

= Italic =
* Wrap the text in single asterisks (*italic*) or [i][/i].

= Underline =
* Wrap the text in underscores (_underline_) or [u][/u].

Please note: text styling does not work for transitions. Sorry.

== Frequently Asked Questions ==

= MEEP! It's not formatting correctly. What do I do? =

First, please make sure you are inputting the text in the right format. (Line spacing is important!)

However, if you're doing it right and it's still not looking right, please go to scrippets.org for troubleshooting help or to submit a bug report.

= The Scrippets are formatted correctly, but the style of the box doesn't fit in with my blog design. What can I do? =

The Scrippets settings panel in your WordPress administrator's page has several settings that you can change to better suit your blog's design.

However, if those options are insufficient, you can modify the scrippets.css file in "wp-scrippets" plugin folder. Be advised that updates to the Scrippets plugin will overwrite your changes, so you should back them up and remember to add them back in whenever the plugin gets updated.

== Release Notes ==

* 1.5   - Fixed screenshot.
* 1.4   - Various bug fixes.
* 1.35  - Fixed bug resulting from having a character name end in "INT" (ie, VINCINT, QUINT).
* 1.3   - Compatibility fix for WordPress 2.8+
* 1.2   - Fixed "FOREST" bug, added version number to scrippetize.php
* 1.1   - Added support for bold, italic, and underlined text.
* 1.0.2 - Fixed bug in wp-scrippets.php that prevented CSS to be added properly for blogs with different WordPress and Blog addresses.
* 1.0.1 - Fixed scrippetize to work with bbPress.
* 1.0   - Release!

== References ==

1. http://johnaugust.com/archives/2008/scrippets-are-go
2. http://johnaugust.com/archives/2008/scrippets-php-and-a-call-to-coders
3. http://johnaugust.com/archives/2004/screenbox
