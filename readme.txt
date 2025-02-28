=== XTCZ Top Box Office ===
Contributors: hkp1990
Donate link: 
Tags: box office widget, box office, hollywood, bollywood, movies, cinema, Top Box Office
Requires at least: 3.6
Tested up to: 4.3
Stable tag: 2.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Real time Weekend Box Office results on your blog.

== Description ==

XTCZ Top Box office provides real time ranking of the weekend box office and always keep users upto date with latest box office results. The data updates automatically every week, no need to do any extra work.

= It has =
* Real time Box Office result.
* Customization options
* Ready shortcode for post, pages or other post type and for wordpress theme
* Ready widget
* Bollywood Box Office (shortcode and widget)

= Required settings =
* After plugin installation, go to `Wordpress Dashboard > Settings > XTCZ Box Office` and save required configuration here.
**Rottentomatoes Key** is required to work this plugin. You can Register Rottentomatoes key from [here](http://developer.rottentomatoes.com/member/register).
* For Bollywood box office no any configration required. And **Rottentomatoes Key** is not required for bollywood box office resutls.

= ShortCode =
* Use `[xtcz_topboxoffice]` shortcode to display top box office in post, pages or other custom post type.
* Use `<?php echo do_shortcode('[xtcz_topboxoffice]'); ?>` php code to display top box office movie list into wordpress theme file.
* Use `[xtcz_bollywood_boxoffice]` shortcode for bollywood box office.

= Optional parameters =
You can also use optional parameters to override saved setting options.

For example:
`[xtcz_topboxoffice theme="standard" img_width="25"]`


= List of optional parameters =
* `theme` : 'fullview' or 'standard' .
* `limit` : Numeric value to show number of movies in the top box office list.
* `img` : Boolean value ( 1 or 0 ) to show/hide thumbnail image.
* `img_width` : Numeric value ( 1 or 0 ) to set width of thumbnail image.
* `mpaa_rating` : Boolean value ( 1 or 0 ) to show/hide movie's Mpaa rating.
* `audience_score` : Boolean value ( 1 or 0 ) to show/hide movie's Audience Score.
* `release_dates` : Boolean value ( 1 or 0 ) to show/hide movie's Release dates.
* `runtime` : Boolean value ( 1 or 0 ) to show/hide movie's Runtime.
* `cast` : Boolean value ( 1 or 0 ) to show/hide movie's Cast.
* `synopsis` : Boolean value ( 1 or 0 ) to show/hide movie's synopsis.


For latest news, box office updates, movie reviews, photos, videos, and more, visit [xtcz.net](http://www.xtcz.net/ "xtcz.net")!

== Installation ==

1. Download "XTCZ Top Box Office" plugin.
1. Upload the 'xtcz-top-boxoffic-movies' directory to your '/wp-content/plugins/' directory, using your favorite method (ftp, sftp, scp, etc...)
1. Activate "XTCZ Top Box Office" from your Plugins page.

= Extra =

1. Visit 'Settings > XTCZ Box Office' and adjust your configuration & settings.
1. Use `[xtcz_topboxoffice]` shortcode or `<?php echo do_shortcode('[xtcz_topboxoffice]'); ?>` in your theme.
1. Use `[xtcz_bollywood_boxoffice]` shortcode or `<?php echo do_shortcode('[xtcz_bollywood_boxoffice]'); ?>` for bollywood box office results.

== Frequently asked questions ==

= How can I call box office list into template =

Place `<?php echo do_shortcode('[xtcz_topboxoffice]'); ?>` in your templates

= How can I override saved settings in shortcode = 

You can use optional parameters to override saved setting. Example: `[xtcz_topboxoffice theme="standard" img_width="25"]`

= Does optional parameters will work for bollywood box office resutls =

No, optional parameters will not work for bollywood box office results.

= Does 'Rottentomatoes Key' required for bollywood box office =

No, Rottentomatoes Key is not required in case of bollywood box office

== Screenshots ==

1. Top Box office widget
2. Top Box office Standard view
3. Bollywood Box office widget
4. Full view with images
5. Full view without images
6. XTCZ Top Box office settings


== Changelog ==

= 2.0 =
* Bollywood Box office shortcode added
* Bollywood Box office widget added

= 1.0 =
* Overall Box office shortcode and Widget

== Upgrade notice ==

= 2.0 =

