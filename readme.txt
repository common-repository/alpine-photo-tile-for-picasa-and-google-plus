=== Alpine PhotoTile for Google Plus and Picasa  ===
Contributors: theAlpinePress
Tags: photos, photostream, stylish, pictures, images, widget, sidebar, gallery, lightbox, fancybox, colorbox, prettybox
Requires at least: 2.8
Tested up to: 3.8
Stable tag: 1.2.6.8
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Stylish and compact plugin for displaying Picasa and Google Plus images in a sidebar, post, or page. 

== Description == 

**Please Note: This plugin is no longer being developed or maintained. If you are a WordPress developer, I encourage you to take this plugin and make it your own.**

The Alpine PhotoTile for Google Plus (formerly Picasa)  is capable of retrieving photos from a particular Google Plus user, a public album, a semi-private album, or a keyword. 
The photos can be linked to the your Google Plus page, a specific URL, or to a Lighbox slideshow. 
Also, the Shortcode Generator makes it easy to insert the widget into posts without learning any of the code. 
This lightweight but powerful widget takes advantage of WordPress's built in JQuery scripts to create a sleek presentation that I hope you will like. 
A full description and demonstration is available at [the Alpine Press](http://thealpinepress.com/alpine-phototile-for-picasa/ "Plugin Demo").

**Alpine PhotoTile for Google+ and Picasa Features:**

* Display Google Plus images in a sidebar, post, or page
* Multiple styles to allow for customization
* Lighbox feature for interactive slideshow (Fancybox, prettyBox, or ColorBox)
* Simple instructions
* Widget & shortcode options
* Feed caching/storage for improved page loading

**Quick Start Guide:**

1. After installing the Alpine PhotoTile for Google Plus plugin on your WordPress site, make sure it is activated by logging into your admin area and going to Plugins in the left menu.
2. To add the plugin to a sidebar, go to Appearance->Widgets in the left menu.
3. Find the rectangle labeled Alpine PhotoTile for Picasa. Click and drag the rectangle to one of the sidebar containers on the right.
4. Once you drop the rectangle in a sidebar area, it should open to reveal a menu of options. The only required information for the plugin to work is Picasa User ID. Enter this ID and click save in the right bottom corner of the menu. Please note that only public photos can be displayed, so check your privacy settings.
5. Open another page/window in your web browser and navigate to your WordPress site to see how the sidebar looks with the Alpine PhotoTile for Picasa included.
6. Play around with the various styles and options to find what works best for your site.

== Installation ==

**Picasa and Google Plus Plugin Installation**

1. Go to the *Plugins->Add New* section of the Admin Panel.
2. Either search for "Alpine PhotoTile for Picasa and Google Plus" or upload the `alpine-photo-tile-for-picasa-and-google-plus` folder using the upload tool.
3. Go to the *Plugins->Installed Plugins* and activate the "Alpine PhotoTile for Picasa and Google Plus" plugin.

**Using the Picasa and Google Plus Widget**

4. Use the widget like any other widget. Go to *Appearance->Widgets* in the left menu. Find the rectangle labeled "Alpine PhotoTile for Picasa and Google Plus". Click and drag the rectangle to one of the sidebar containers on the right.
5. Customize Alpine PhotoTile for Picasa and Google Plus plugin based on your preference.

**Using the Picasa and Google Plus Shortcode**

6. A shortcode is a line of texted used for loading plugins within WordPress pages or posts. Rather than explaining how to setup the shortcode, I have added a tool to the Alpine PhotoTile for Picasa and Google Plus plugin that generates the shortcode for you. Visit the "Shortcode Generator" on the Picasa and Google Plus plugin's settings page (*Settings->AlpineTile: Picasa and Google Plus->Shortcode Generator*).


== Frequently Asked Questions ==

= How do I find my Google Plus (Picasa) User ID or Album ID? =

Since Picasa has been combined with Google Plus, Picasa photo albums are also Google Plus photo albums. This also means that there are different ways of finding your ID's depending on whether you start at the Picasa website or your Google Plus page.


*Starting at Google Plus:*

  1. Log into [Google Plus](http://plus.google.com/ "Google Plus").

  2. In the left sidebar, click "Photos". From the top menu, click "Albums" and then click on one of your albums.

  3. The URL address should now be something like:

    "https://plus.google.com/photos/112515131248168353825/albums/5828938068968925825",

    where 112515131248168353825 is your User ID and 5828938068968925825 is the Album ID.


*Starting at Picasa:*

  1. Log into [Picasa](http://picasaweb.google.com/ "Picasa").

  2. From the list of photo albums, click on the one you want to show.

  3. The URL address should now be something like:

    "https://picasaweb.google.com/112515131248168353825/NewMexicoSummer2011",

    where 112515131248168353825 is your User ID and NewMexicoSummer2011 is the Album ID.

  4. (Optional) If you click on the "RSS" link on the right side of the page, you will arrive at a url similar to:

    "https://picasaweb.google.com/data/feed/base/user/112515131248168353825/albumid/5828938068968925825?alt=rss&kind=photo&hl=en_US",

    where 112515131248168353825 is your User ID and 5828938068968925825 is the Album ID. Here the Album ID is shown as a number rather than text, as in the Google Plus example.

= How do I set a photo album to public? How do I change my privacy settings? =

Since Picasa has been combined with Google Plus, Picasa photo albums are also Google Plus photo albums. This also means that there are different ways of changing your settings depending on whether you start at the Picasa website or your Google Plus page.


*Starting at Google Plus:*

  1. Log into [Google Plus](http://plus.google.com/ "Google Plus").

  2. In the left sidebar, click "Photos". From the top menu, click "Albums" .

  3. Near the top left, there should be a button labeled "Sharing Settings".

  4. Make sure the album you want to show is set to Public and is unlocked.


*Starting at Picasa:*

  1. Log into [Picasa](http://picasaweb.google.com/ "Picasa").

  2. From the menu near the top of the page, select "My Photos".

  3. Above the left-most photo album should be a link labeled "Edit Visibility".

  4. Make sure the album you want to show is set to Public.

= I'm getting the message "Google Plus (Picasa) feed was successfully retrieved, but no photos found". What does that mean? =

This message simply means that while no distinguishable errors occurred, the plugin found your feed to be empty.

= I'm getting the message "Google Plus (Picasa) feed not found. Please recheck your ID". What does that mean? =

This message can mean two things. First, it can indicate that the username or custom url were input incorrectly, causing the feed to fail. In this case, you should try to correct and re-save your IDs.

Second, this message can also mean that the server your WordPress site is being hosted on has prevented the feed from being retrieved. While it is rare, we have encountered web-hosts that disable the feed fetching functions used in the PhotoTile plugin. If this is the case, there is nothing we can do to override or work around the settings on your host server.

= Can I insert the plugin in posts or pages? Is there a shortcode function? =

Yes, rather than explaining how to setup the shortcode, I've created a method of generating the shortcode. Check out the Shortcode Generator on the plugin's settings page ( Settings->AlpineTile: Picasa & Google Plus->Shortcode Generator).

= Why doesn't the widget show my most recent photos? =

The plugin caches or stores the Google Plus (Picasa) feed for three hours (see Caching above). If the new photos have still not appeared after this time, it is possible that Picasa is responsible for the delay.

= How many photos can I show? =

As of version 1.2.0, up to 100 photos can be retrieved and displayed.


*If you have any more questions, please leave a message at [the Alpine Press](http://thealpinepress.com/alpine-phototile-for-picasa/ "Plugin Demo").
I am a one-man development team and I distribute these plugins for free, so please be patient with me.*


== Changelog ==

= 1.2.0 =
* Rebuilt Alpine Photo series to work with Picasa and Google Plus
* Rebuilt plugin structure into OBJECT
* Combined all Alpine Photo Tiles scripts and styles into identical files
* Improved IE 7 compatibility
* Added custom image link options
* Added Fancybox jQuery option
* Fixed galleryHeight bug
* Implemented fetch with wp_remote_get()

= 1.2.1 =
* Rebuilt admin div structure
* Fixed admin css issues

= 1.2.2 =
* Added aspect ratio options for gallery style
* Added key generator function
* Added get_image_url() functions
* Object oriented id, options, results, and output storage
* Object oriented display generation

= 1.2.3 =
* Added FancyboxForAlpine (Fancybox Safemode)
* Added choice between Fancybox, prettyBox, and ColorBox
* Added hidden options, including custom rel for lightbox

= 1.2.3.1 =
* Fixed cache retrieval

= 1.2.4 =
* Restructured plugin objects and reassinged functions
* Object oriented message, hidden, etc.
* Added option to disable right-clicking on images
* Added updateGlobalOptions and removed individual option calls
* Added donate button
* Fixed lightbox param option

= 1.2.5 =
* Added fallback to dynamic style and script loading using jQuery
* Various small fixes
* Moved cache location
* Updated ColorBox plugin
* Set Object params to private and implemeted set, check, and get function
* Implemeted do_alpine_method call
* Created active options and results functions

= 1.2.6 =
* Fixed jQuery bug (Removed all <> tags from inline scripts)
* Add stripslashes text sanitization
* Changed lightbox parameters option from CSS to stripslashes sanitization
* Small fix: Album id in cache key and keyword filter

= 1.2.6.2 =
* Added authkey for semi-private photo albums. Includes filter to add 'Gv1sRg' to Google+ authkeys. 

= 1.2.6.3  =
* Check compatibility with WP 3.8
* Small CSS changes (Padding and hover white background)
* Replaced deprecated jQuery APIs  ( .load() and .browser )
* Updated prettyPhoto and colorbox

= 1.2.6.5 =
* jQuery backwards compatibility ( .bind() function for jQuery v1.6.3 and less )

= 1.2.6.6 =
* Pretty Photo Update

= 1.2.6.7 =
* Fixed Admin Tabs

= 1.2.6.7 =
* End of development notice

= TODO =
* Change to FancyBox 2
* Add caption to display
* Rebuild jQuery display
* Check with Contact Form 7