simple-flickr-set
=================

A wordpress plugin for embedding simple slideshows from Flickr photosets.

###Description###

This allows the user to embed auto-playing looping Flickr galleries with a simple shortcode using javascript and css (no flash!).


###Requirements###

PHP 5.3+
This has been tested on Wordpress 3.5.1 and newer.  It is powered by just a few lines of javascript.  

###Installation###

The most simple way to install this is to go to the plugins directory (/wp-content/plugins) of your Wordpress installation and clone this repo.  Then, in the admin console, go to Plugins->Installed and activate it.  That's it!

###Admin Interface###

To begin simply add your Flickr API key and url in the "Simple Flickr Set" menu (requires Editor or above).  The page will then list all your photosets and give you a shortcode to paste into your post or page.


###Using the shortcode###

The most basic way is to simply use a photoset ID (the admin page will look these up for you):

```[simple-flickr set=72157633015103114]```

You can additionally specify height and width, using any valid CSS.  It defaults to 500x460, the default Flickr iframe embed (back when that worked...)

```[simple-flickr set=72157633015103114 height=500px width=500px]```

###What else can I do?###

Rather than using inline styles, the plugin adds CSS to the page, which means all elements of the plugin are easily selectable by CSS.  Though the slideshow is responsive by default, you can add any additional styling right in your themes CSS. 
