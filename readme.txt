=== Instant Adsense ===
Contributors: danniocean
Tags: adsense, plugin, post, posts, admin, ads, google, ad, ad manager, adsense insertion, ad insertion
Requires at least: 1.5
Tested up to: 3.4
Stable tag: 3.05

Automatically insert Google Adsense ads in to your posts on the fly.

== Description ==

Instant Adsense is a Free and Open Source Wordpress plugin which is able to automatically insert google adsense ads in to your posts on the fly. it will insert your ad code into all of them automatically. You can control all aspects of your ad's display and position. Just specify ad color and position in the plugin options, your ad code is automatically generated and inserted. Advanced users can add html and css code before and after the ad to have total control of the ad display.

Features:

1. Automatically insert Google Adsense ads in to your blog posts.
2. No manual work required, ad code is dynamically inserted into your existing and new posts.
3. You can optionally specify not to show ads in a post by using tag <!==noadsense==>
4. You can optionally specify where to start the ads in a post by using tag <!==adsensestart==>
5. You can optionally specify where to stop the ads in a post by using tag <!==adsensestop==>
6. Decrease ad blindness by giving you the option to randomly place your ad within your posts.
7. You can optionally define absolute ad position instead of random position.
8. You can optionally define random ad network to maximize earnings from both networks.
9. Allow you to pick how many total ads to show on one page.
10. Allow you to pick how many ads to show in one post.


== Installation ==

1. Upload "instant-adsense" directory to the "/wp=content/plugins/" directory
2. Activate the plugin through the "Plugins" menu in WordPress
3. Configure the plugin in the "Settings"->"Adsense" menu (the plugin must be configured with your adsense publisher id to start working).

== Frequently Asked Questions ==

= Do I need to get adcode Google? =

No, the plugin will automatically generate the ad code for you, you just need to put in your publisher id and optionally a channel id.

= Do I need to insert any tags into my posts to make it work? =

No, the plugin will automatically insert adsense ads into ALL your posts by default, there is nothing to be done manually, you only need to insert tags when you do not want ads to appear in a certain post or if you want to specify a certain point where the ad should not appear.

= Does this plugin change my post content in the database? =

No, this plugin inserts the ad code only after the content has been retrieved from the database by wordpress, your content is not changed. So you can just disable this plugin and all the in=post ads would be gone from your blog.

= Why does my page only show white blocks but not ads? =

First make sure you put only numbers in the adsense account number field, meaning there should be no ca=pub= or pub=, only numbers. If it still doesn't work, then make sure you have less than 3 google ads on your entire page or else google will automatically turn your ads into white block.



== Changelog ==

= 3.05 =
 - Removed insertion of plugin author Adsense ID into roughly 10% of inserted Adsense links

= 3.04 =
 - /home/soap/projects/instant-adsense/tags/3.04/readme.txt pulled remaining Yahoo references from plugin
 - minor UI updated
 - removed phone-home capability
 - removed aes encrypter
 - readme updates :]

= 3.00 =
 - disabled all Yahoo options in interface (no longer supported)
 - disabled backend hooks for YPN accounts
 - cleaned up some minor PHP

= 2.01 =
 - added WP MU compatiblility
 - various minor error fix

= 1.92 =
 - made clarification to instructions

= 1.90 =  
 - made some UI changes 
 - added colorpicker to the settings page to pick color directly

= 1.84 =  
 - start to use wordpress.org changelog function  
 - added function to recognize client id with pub= in front of the number

= 1.83 =  
 - tidy up some code to avoid confusion.
