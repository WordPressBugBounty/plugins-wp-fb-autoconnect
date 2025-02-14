=== WP Social AutoConnect ===
Contributors: Justin_K
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=T88Y2AZ53836U
Tags: facebook login, facebook connect, login with facebook, social login, buddypress
Requires at least: 2.5
Tested up to: 6.3
Stable tag: 4.6.2

A lightweight but powerful Facebook login plugin, easy to setup and transparent to new and returning users alike.  Supports Buddypress. Previously called WP-FB-AutoConnect.

== Description ==

The simple concept behind WP-FB AutoConnect is to offer an easy-to-use widget that lets readers login to your blog with either their Facebook account or local Wordpress credentials. Although many "Facebook Connect" plugins do exist, most of them are either overly complex and difficult to customize, or fail to provide a seamless experience for new  visitors. I wrote this plugin to provide what the others didn't:

* Full support for both Wordpress and Buddypress.
* No user interaction is required - the login process is transparent to new and returning users alike.
* Existing users who connect with FB retain the same local user accounts as before (matched via e-mail).
* New visitors will be given new user accounts, which can be retained even if you remove the plugin.
* Facebook profile pictures can be used as avatars.
* No contact with the Facebook API after the login completes - so no slow pageloads.
* No 3rd party services: your site talks directly to Facebook, through an app created and owned by you.
* Won't bloat your database with duplicate user accounts, extra fields, or unnecessary complications.
* Custom logging options can notify you whenever someone connects with Facebook.
* A powerful set of hooks and filters allow developers to easily tailor the login process to their personal needs: redirect to a custom page, fill xProfile data with information from Facebook, setup permissions based on social connections, and more.
* Fully HTML/CSS valid.

== Premium Addon ==

In addition to the free features listed above, I also offer a Premium addon to provide some more advanced functionality.  The following is an abbreviated list of Premium features; a more complete list, along with details on each item, is available on the [plugin homepage](https://www.justin-klein.com/projects/wp-fb-autoconnect/#premium):

* Multisite Support
* Shortcode Support
* Image-based/styleable login buttons
* Cache Facebook avatars to your local server
* Allow users to manually associate/disassociate their existing accounts with Facebook
* Automatically populate BuddyPress X-Profiles with information from Facebook
* Announce Facebook logins to the BuddyPress Activity Stream
* Show an AJAX spinner to indicate login-in-progress
* Add a Facebook button to the comment form, login form, registration form, and WPMU signup form
* Customize the redirect URL for first-time visitors, returning visitors, and logged-out visitors
* Restrict autoregistration to Facebook friends, Facebook fans, explicitly invited users, everyone, or no one
* Send a customizable welcome mail to autoregistered users
* Customize the role assigned to autoregistered users
* Show/Hide/Customize the Widget's links, checkboxes, and textfields.  Show the logged-in user's avatar in the Widget.
* Priority support
* ...And more

== Donate ==

Countless hours have gone into developing, maintaining, & supporting this plugin. Just keeping it running requires ongoing work due to Facebook's ever-changing API & Wordpress' frequent updates. If you find it useful, please consider supporting its continued development by purchasing the Premium addon or [making a donation](https://www.justin-klein.com/projects/wp-fb-autoconnect/#donate) of any amount.

== Privacy ==

This plugin uses the Facebook API to fetch data from Facebook. The data is used to automate user logins, and/or to automate the creation of new local Wordpress user accounts. The data may therefore be copied & stored in the WordPress database, and can be removed by deleting any Facebook-linked user accounts. Usage of this plugin means the site administrator is consenting to [Facebook's data policy](https://www.facebook.com/policy.php). Note that using the Facebook API requires loading some JS from Facebook, which may track visitors. This plugin does not use any 3rd party intermediary for processing logins or otherwise - all data is exchanged directly between your site & Facebook.

In addition, the Premium addon (if purchased & installed separately) may connect to the developer's web store to check for updates & for license verification. This check does not transmit any information about your users, and is used solely to check for updates and for licensing verification.

== Installation ==

1. Download the latest version from [here](http://wordpress.org/extend/plugins/wp-fb-autoconnect/), unzip it, and upload the extracted files to your plugins directory.
2. Login to your Wordpress admin panel and activate the plugin.
3. Navigate to Settings -> WP-FB AutoConn.
4. Follow the steps shown in the admin panel to create & register your Facebook app.
5. If you're using BuddyPress, a Facebook button will now automatically appear in its built-in login widget.  Otherwise, navigate to Appearance->Widgets and add the WP-FB AutoConnect widget to your sidebar. 

That's it - users should now be able to use the widget to login to your blog with their Facebook accounts.

For more information on exactly how this plugin's login process works and how it can be customized, see the [homepage](https://www.justin-klein.com/projects/wp-fb-autoconnect).


== Frequently Asked Questions ==

[FAQ](https://www.justin-klein.com/projects/wp-fb-autoconnect#faq)


== Screenshots ==

[Screenshots](https://www.justin-klein.com/projects/wp-fb-autoconnect#demo)


== Changelog ==
= 4.6.2 (2023-07-01) =
* Fix a minor CSRF vulnerability

= 4.6.1 (2023-04-28) =
* Updated the FB app setup instructions (they changed their process yet again)
* Tested with WP 6.2

= 4.6.0 (2022-11-05) =
* Add an admin panel note about how to enable the Legacy Widget block
* Fix a (harmless) error_log when adding the widget in the Legacy Widget block
* Updated the FB app setup instructions (they changed their process yet again)
* Tested with WP 6.1

= 4.5.9 (2022-02-06) =
* Added a check to the admin panel to ensure that the current theme supports widgets.
* Added another step to the Facebook app setup instructions.
* Removed the Premium widget teaser in the free widget, & replaced it with a small / less obtrusive text-only note.

= 4.5.8 (2021-07-17) =
* Updated the FB app setup instructions (they changed their process yet again)
* Minor CSS fixes for WP 5.8

= 4.5.7 (2021-03-24) =
* Login errors due to "Missing redirect URL" will not be sent unless the "Include 'Missing POST Data' error events" option is enabled (due to recently increased activity by spambots)
* Add css class to admin panel buttons
* Change the donate link
* Tested with WP 5.7

= 4.5.6 (2020-12-09) =
* Updated the FB app setup instructions (they changed their process yet again)
* Tested with WP 5.6

= 4.5.5 (2020-09-09) =
* Minor: Added a bitcoin donation address to the admin panel & readme
* Tested with WP 5.5

= 4.5.4 (2019-11-25) =
* Update FB app setup instructions in the admin panel
* CSS tweaks
* Fix error_log that may appear when accessing the admin panel if your hosting environment blocks outbound connections to Facebook
* Tested with WP 5.3

= 4.5.3 (2019-10-03) =
* More fixes per WP's security audit

= 4.5.2 (2019-10-03) =
* More input sanitization

= 4.5.1 (2019-09-30) =
* Remove the (old/unused) "delay redirect after login" debug option to satisfy WP.org's security check
* Sanitize input text in the admin panel

= 4.5 (2019-09-25) =
* Change the plugin name from WP-FB-AutoConnect to WP Social AutoConnect to satisfy Facebook's ridiculous lawyers

= 4.4.1 (2019-06-27) =
* Update FB app setup instructions in the admin panel & readme
* Update logging
* Tested with WP 5.2.2 & PHP7

= 4.4 (2018-06-26) =
* Update Facebook API version to v3.0
* Add an option to request the user's profile URL. Facebook now requires extra permissions to do this, so if you want to continue getting your visitors' profile links, you'll need to enable this option & submit your app for review by Facebook.
* Add a filter to show the Facebook profile URL on the WP user profile page, if available. These URLs will no longer be written to the standard Wordpress "Website" profile field, as Facebook broke their scoped user id url scheme & they now return URLs that are too long to fit in the standard WP users table.
* Add privacy policy
* Remove the "Announcement" feature. Facebook broke this several years ago & it has been unusable for some time.
* Update documentation in the admin panel & readme

= 4.3.3.1 (2018-05-02) =
* Replace botched svn commit

= 4.3.3 (2018-05-02) =
* Fix for FB breaking autoregistration (by changing their 'scoped profile urls' to be so absurdly long they can no longer fit in the wp_users table)
* Fix for WP not properly reporting wp_insert_user() failures in some situations
* Add a line to Support Info admin page for allow_url_fopen
* Some additional detail in debug logs
* Tested with WP 4.9

= 4.3.2 (2017-02-18) =
* Update the instructions for setting up a Facebook app...again
* Tested with WP 4.7.2

= 4.3.1 (2016-12-09) =
* Slightly increase vertical spacing between the widget fields to better reflect the default Wordpress themes
* CSS fix for TwentySeventeen theme
* Fix to restore the Facebook button to the Log In widget included with BuddyPress
* Update the instructions for setting up a Facebook app, which they've changed for the billionth time
* Tested with WP 4.7

= 4.3.0 (2016-07-19) =
* Facebook API calls are now versioned (v2.7)
* Detect the actual API version used by your app, & show under 'Support Info' 
* Facebook JS api now uses sdk.js instead of all.js
* Remove the FB.init ChannelURL & oauth params (deprecated)
* Fix error_logs that may appear if WP_DEBUG is defined & usage stats are enabled
* Tested with WP 4.5.3

= 4.2.2 (2016-04-21) =
* Fix deprecated Widget constructor
* Verified with WP 4.5

= 4.2.1 (2016-01-19) =
* Fix a php shorttag

= 4.2.0 (2016-01-15) =
* Support for translate.wordpress.org
* Fix a notice when visiting the "Groups" page on BP sites with WP_DEBUG defined
* Show a preview of the Premium widget options in the Basic widget

= 4.1.2 (2015-12-03) =
* Fix notices when using the "Uninstall" feature
* Tested with WP 4.4

= 4.1.1 (2015-08-09) =
* Update PHP4-style class constructors (for compatibility with WP 4.3)
* Update code for sending admin notifications (for WP 4.3)
* Add description to the "E-Mail" option in the admin panel

= 4.1.0 (2015-07-10) =
* Compatilibity fix for Graph API v2.4 when fetching user information
* Fix for checking API availability in the Support Info tab
* Fix a warning that may appear if WP_DEBUG is defined and the 'request email addresses' option is disabled

= 4.0.10 (2015-05-13) =
* Change the default display_name for autoregistered users to the full name (instead of just the first name)
* Revise the setup instructions (BP no longer ships with its own default theme)
* Revise documentation for the "wall announcement" feature, which Facebook has decided to kill off.
* New filter: wpfb_candidate_users_query
* Additional safety check to prevent spambot logins
* Tested with WP 4.2.2

= 4.0.9 (2015-03-31) =
* Fix deprecated function call in admin panel
* Fix extra slashes getting added when saving login announcements
* Fix Spanish translations
* Include fb userdata in wpfb_login
* Remove Premium option for Group-based login restrictions; Facebook has apparently changed their policies, and now refuses to approve the user_groups permission for anyone. [Reference](https://developers.facebook.com/docs/facebook-login/permissions/v2.3#reference-user_groups).

= 4.0.8 (2015-01-24) =
* If you use the "Facebook profile pictures as avatars" feature and your theme displays avatars larger than 50x50, they will now appear MUCH cleaner.
* Add wpfb_avatar_size filter, to specify the dimensions of Facebook avatars
* Update the premium admin tab to show some recently-added features.
* Update .po/.mo files

= 4.0.7 (2014-12-24) =
* Add admin panel notes about Facebook's new review process
* Tested with WP 4.1

= 4.0.6 (2014-11-27) =
* Fix potential vulneratility with some unescaped options in the admin panel
* Include userdata in the error message if wp_insert_user() fails
* Tested with WP 4.0.1

= 4.0.5 (2014-09-24) =
* Fix the "Application request limit reached (#4)" error when validating your appid & secret

= 4.0.4 (2014-09-19) =
* Update Facebook App setup instructions in the admin panel & readme (they changed them yet again...)

= 4.0.3 (2014-09-05) =
* Updated Spanish translations
* Updated Serbian translations
* Confirmed compatibility with WP 4.0

= 4.0.2 (2014-08-12) =
* Fix to prevent WPEngine's "Login Protection" from breaking Facebook logins

= 4.0.1 (2014-08-12) =
* Just a version number mixup in the Wp.org repository 

= 4.0.0 (2014-08-12) =
* By popular demand, this plugin finally supports gettext localization.  Please submit your translations - or let me know if I've missed any strings (there are bound to be a few!)
* Add Spanish translation (thanks to Ogi Djuraskovic from [firstsiteguide.com](http://firstsiteguide.com))
* Add Serbian translation (thanks to Ogi Djuraskovic from [firstsiteguide.com](http://firstsiteguide.com))
* FB Graph API v2.0 introduces scoped userIDs, meaning profile urls can no longer be inferred from IDs alone.  I now explicitly store Facebook profile urls to usermeta.
* FB Graph API v2.1 removes support for FQL; I've rewritten the avatar-fetching code so they it will work with newly-created apps.
* FB Graph API v2.1 breaks the "Enforce access to e-mail" premium feature.  Until I have time to rewrite it, I've added a quick check to prevent it from breaking logins (note: this only applies to newly-created apps; the feature will continue work if you were already using it before).
* Improve the Support Information tab of the admin panel
* Clarification to setup instructions

= 3.1.11 (2014-06-13) =
* Add a new debug option to disable the "Missing POST Data" login logs
* Add instructions to the admin panel for submitting your app for review (now required to post announcements to your users' walls)
* Change the publish_stream permission to publish_actions
* Confirmed working with WP 3.9.1

= 3.1.10 (2014-04-17) =
* Tested with WP 3.9
* Include the WP version in login logs

= 3.1.9 (2014-03-05) =
* CSS fix for twentyfourteen theme on iPhone & Android
* Change email to link in the copyright notice

= 3.1.8 (2014-02-17) =
* Fix a critical bug that sometimes causes users to be logged in under the wrong account 32-bit servers

= 3.1.7 (2014-02-11) =
* Facebook has rearranged their developers page again; updated the setup instructions in the admin panel & readme
* Checked compatibility with WP 3.8.1

= 3.1.6 (2014-01-10) =
* Minor security fix
* Update the summary in the 'plugins' page of the WP admin panel
* Update the Premium admin panel tab with features from addon v33
* Update the ReadMe (tagline, list premium features, etc)

= 3.1.5 (2013-12-13) =
* Verified compatibility with WP 3.8

= 3.1.4 (2013-10-30) =
* Add a "more info" link to the debug option for enabling logs (in the admin panel).
* Add a "callback" param to jfb_output_facebook_btn (required to support an in-progress premium feature)
* Add an admin panel warning if W3-Total-Cache is detected (with simple instructions for debugging an issue it sometimes causes)
* Add an admin panel warning if WPEngine is detected (with simple instructions for debugging an issue it sometimes causes)
* Tested on WP 3.7.1

= 3.1.3 (2013-10-24) =
* Fix PHP warnings when saving plugin options with WP_DEBUG enabled (Thanks Christian Wach!)
* Replace "Mouseover for more" info links in the admin panel with "Click for more," which uses a more mobile-compatible lightbox.
* Update WP compatibility number

= 3.1.2 (2013-06-27) =
* Widget uses wp_lostpassword_url() instead of site_url( 'wp-login.php' ), so that wp-login.php can be moved/renamed.
* Remove the "cURL not found" admin panel warning; it's no longer required (as of v3.0.0) 

= 3.1.1 (2013-06-20) =
* Widget uses wp_login_url() instead of site_url( 'wp-login.php' ), so that wp-login.php can be moved/renamed.

= 3.1.0 (2013-05-07) =
* Revisions to satisfy wp.org's (apparently) new, stricter repo rules...:
* Instead of redirecting to _process_login.php, _process_login.php is always included and logins are handled during "init" (via a $_POST check)
* Remove __inc_wp.php
* Remove _autologin.php (it was extremely outdated & not necessary to the core plugin)
* Remove unused jQuery file
* Remove licensecheck
* Remove the auths (& add *option* to report usage statistics)
* Update the app setup instructions to mention Sandbox Mode (which FB now seems to be enabling by default)

= 3.0.1 (2013-03-08) =
* Update WP compatibility number
* Fix the image-based button preview in the admin panel teaser

= 3.0.0 (2013-03-07) =
* IMPORTANT: If you're a Premium user, please view [FAQ46](https://www.justin-klein.com/projects/wp-fb-autoconnect#faq46) BEFORE installing this update.
* IMPORTANT: If you've implemented any custom actions that utilize the Facebook API instance provided by this plugin, you'll need to update your code to use graph URLs instead (i.e: jfb_api_get("https://graph.facebook.com/me?access_token=".$arg['access_token'])).  Further examples can be found on the plugin documentation page.
* This update completely eliminates the dependance on the old Facebook PHP API, which will speed up logins, significantly reduce memory usage, and prevent errors on localhost servers without a public URL.
* This update also adds support for Premium addon v30, which provides many new features (including the ability to use image-based / css-styleable login buttons).

= 2.5.12 (2013-03-04) =
* Display a warning for users who upload the premium addon to the wrong directory
* More descriptive error message for "Missing POST Data (access_token)"
* Cleanups to admin panel tab switching; refreshing the panel now restores the previously-shown tab

= 2.5.11 (2013-02-19) =
* Widget login form uses site_url (to support FORCE_SSL_LOGIN)
* Login callback redirects to _process_login.php over https if FORCE_SSL_LOGIN is enabled
* wp_login was getting a bad 2nd parameter when called during an autoregistration; fixed
* Check for a premium function before choosing the avatar cache dir
* Update the eStore link in one admin panel warning

= 2.5.10 (2013-02-08) =
* Pass the facebook UID into _process_login.php so it can be logged.  This is useful for debugging failed login attempts, as we can determine if they were triggered by a valid user (and if so, who).
* Add appID and appValid to the Support Info tab
* Update the cURL test on the Support Info tab 
* More descriptive instructions for users who've moved wp-config 

= 2.5.9 (2013-01-15) =
* Fix the login button jumping around on initialization (thanks to yet another bug introduced by Facebook)   
* Compatibility fix for BP Avatar Bubble

= 2.5.8 (2012-12-25) =
* Fix compatibility with woocommerce (wp_login action was supposed to take 2 parameters)
* Remove xmlns:fb from the header tag.  It doesn't seem to be necessary for any modern browsers, and breaks validation for HTML5.  If you find it necessary, you can always re-add it with a simple filter.

= 2.5.7 (2012-12-23) =
* Fix for validating the API key/secret on servers with invalid SSL cert

= 2.5.6 (2012-12-23) =
* jQuery is not working for some users on WP3.5.  I explicitly enqueue it now.
* Fix mistake with prelogin error check

= 2.5.5 (2012-12-22) =
* Fix double-counting of logins (hopefully)
* Add a keepalive event & prelogin error check

= 2.5.4 (2012-12-20) =
* Fix a minor bug with new user notifications in WP3.5
* Update WP compatibility number

= 2.5.3 (2012-12-18) =
* Fix a harmless warning that appears on BP when WP_DEBUG is defined
* Another minor cleanup to the button-outputting code
* Add new filter

= 2.5.2 (2012-12-10) =
* Oops - very minor revision from 2.5.1 :)

= 2.5.1 (2012-12-10) =
* Combine the two profile picture queries into one (shave ~0.3s off of login time)
* Eliminate action wpfb_output_button, and cleanup jfb_output_facebook_btn for clarity (and in prep for a future change)

= 2.5.0 (2012-11-29) =
* I've eliminated the need for the Facebook PHP SDK entirely.  Although it's still included and passed to the actions/filters for backwards-compatibility, calls to the Graph API should now performed via jfb_api_get() and jfb_api_post(), using the access_token provided.  Specific changes:
* Rename jfb_get() to jfb_api_get()
* Add jfb_api_post() for API calls requiring HTTP POST
* Facebook JSON responses are decoded to associative arrays rather than objects (to match the format of the PHP SDK)
* Rename "accessToken" to "access_token" to better match the naming convention used by the Graph API
* Update jfb_post_to_wall() to avoid using the $facebook class
* Update all queries & error checks in _process_login.php to avoid using the $facebook class
* Rearrange things in _process_login.php, putting the $facebook initialization code into a "to deprecate" block
* Get rid of the 2.3.6 'one-time update' code to store the app access token in the DB

= 2.4.1 (2012-11-27) =
* Explicitly pass & check for the user access token in _process_login.php
* Provide the user access token to wpfb_session_established, wpfb_connect, wpfb_existing_user, wpfb_inserting_user, wpfb_inserted_user, and wpfb_login (so you can use it to query the Graph API in your addons)
* Cleanup jfb_output_facebook_callback()
* Fix a harmless notice that may appear if you have WP_DEBUG defined

= 2.4.0 (2012-11-26) =
* I've eliminated the old REST PHP library, which was only being used to validate the AppID & Secret in the admin panel; validation is now done with Graph.  IMPORTANT: If you've been using this plugin since the old "App Key" days (over a year ago) and the AppID in your admin panel is an old alphanumeric value, you should replace it with the new numeric-only AppID shown in your App's settings on Facebook.
* Include the AppID in login logs

= 2.3.11 (2012-11-19) =
* Add a few more things to the Support Info tab
* Update the Premium Options tab to reflect the latest addon version

= 2.3.10 (2012-11-11) =
* Fix error reporting for a rare login bug
* Use wp_mail() instead of php mail() to send login logs (for servers with custom mail configurations)
* Include a stylesheet with some default widget styles
* Show "WP-FB AutoConn+" in the admin menu if the Premium addon is installed

= 2.3.9 (2012-11-01) =
* Improve browser detection for login logs (+ add detection for Android & iPad)
* Login logs include the full useragent string

= 2.3.8 (2012-10-27) =
* Get rid of old nonce debugging code
* Move the nonce check back to before the Facebook connection

= 2.3.7 (2012-10-22) =
* Bug fix when error-detecting the token in the admin panel

= 2.3.6 (2012-10-21) =
* When connecting with Facebook in the admin panel, cache the app token to the database (so addons/customizations can use it to access the API later)

= 2.3.5 (2012-10-20) =
* Add log messages when each action/filter is run in _process_login.php (for debugging add-ins)
* Move the Facebook connection to *before* the nonce check
* Add a new action 'wpfb_session_established,' so we can talk to Facebook before anything else happens 

= 2.3.4 (2012-10-16) =
* Users who didn't update to 2.3.1 when it was released may now have some malformed avatar URLs in their db (resulting in frontend 'strpos' error messages); this update will fix those avatars.  Note:  Please remember to update your plugin whenever a new version is released, as Facebook changes their API regularly and skipping updates can sometimes lead to unpredictable behavior.

= 2.3.3 (2012/08/20) =
* Fixed a problem with Curl detection caused by FB changing things without telling people

= 2.3.2 (2012/08/16) =
* Facebook has yet again broken their API, causing avatars to always fetch size 50x50 (even for the "large" size used by BuddyPress and some 3rd party themes).  This update should work around FB's bug, returning avatars to their former behavior.

= 2.3.1 (2012/07/21) =
* Fix a rare bug with avatar fetching

= 2.3.0 (2012/02/22) =
* Major performance improvement: logins should now be substantially faster on sites with large user databases.

= 2.2.2 (2012/02/22) =
* Update version compatibility number
* The 'Failed to get the Facebook User Session' error now refers to a specific FAQ.
* Add support for debugging memory usage and execution time (via the email logs)
* Combine Admin notices into one action
* Update the admin panel's premium teaser to include newly-added features

= 2.2.1 (2012/01/10) =
* Add an admin panel check to warn users whose servers don't have CURL installed
* Add an admin panel check to warn users whose servers dont have JSON installed
* Add a new tab to the admin panel with "Support Info" (to include when reporting a bug/issue)

= 2.2.0 (2011-12-17) =
* Nonce fix to resolve a conflict with Buddypress Groups, and potential validation issues with other plugins that use the default nonce name/action (thanks gbellucci!)
* Check for compatibility with WP3.3

= 2.1.9 (2011-12-13) =
* Removed an old (now unused) database option that was getting written on every pageload (thanks Aaron Frerichs!)

= 2.1.8 (2011-11-28) =
* Removed plugin sponsorship messages.  See [Automattic Bullies WordPress Plugin Developers -- Again](http://gregsplugins.com/lib/2011/11/26/automattic-bullies/).

= 2.1.7 (2011-11-25) =
* Fix: wpfb_extended_permissions filter was not being applied if neither "post to wall" nor "request email" options were checked.
* Add new BuddyPress XProfile mapping to the premium admin panel

= 2.1.6 (2011-11-24) =
* All new TABBED Admin panel!
* Better error reporting for "wp_insert_user failed"
* Add a note to the "Delete All Options" section of the admin panel
* Eliminate old admin panel code related to updating .htaccess rules for autologin
* Fix: Username style was defaulting to the legacy format on Buddypress
* Fix: Admin panel was not properly showing when the new username format is selected

= 2.1.5 (2011-11-22) =
* The "Buddypress-Friendly" username format (First.Last) seems to create issues with author links in Wordpress, so I've added a new "First_Last" option (and left the old option there for legacy support only).  If you have multiple authors and are using the "First.Last" format, you may want to change your username format. 

= 2.1.4 (2011-11-16) =
* Move the Wall Announcement code into a filter, so it can be removed/replaced/customized if desired
* Update WP compatibility number

= 2.1.3 (2011-11-15) =
* Fixed a bug where the plugin was incorrectly stripping some language_attributes, causing problems for rtl languages.

= 2.1.2 (2011-11-08) =
* Eliminate the outdated xd_receiver.htm file
* Eliminate the outdated validate_php5.php file
* Update the instructions for creating an app (Facebook has changed things around yet again)
* Use https instead of http in channel.html to prevent insecure content warning
* Fix "wp_insert_user failed" bug (since 2.1.0)

= 2.1.1 (2011-10-29) =
* Fix a critical bug introduced in 2.1.0: not prompting for e-mail *could* result in false user account matches (i.e. logging someone in as someone else).  Please update now!
* Replace deprecated get_settings() with get_option()
* Add rel=nofollow to the lostpassword link

= 2.1.0 (2011-10-01) =
* Update to use OAuth 2.0.  NOTE: Premium users must also update their addons; see the support page for how.

= 2.0.9 (2011-07-20) =
* Don't apply sanitize_title to nicenames

= 2.0.8 (2011-07-10) =
* Fix for completely non-alphanumeric usernames

= 2.0.7 (2011-07-06) =
* Filtered avatars use the $alt provided by WP core (or theme)

= 2.0.6 (2011-07-01) =
* Fixed bug with avatar caching on BuddyPress

= 2.0.5 (2011-06-14) =
* Increase version campatiblity number
* Remove legacy API code from _process_login.php
* Remove legacy code for registering email hashes (Facebook has eliminated that functionality from their API for some reason...)
* Update instapopup to work with the new API
* Fixed avatars in Settings -> Discussion when avatar fetching is enabled
* Apply sanitize_title to the nicename (thanks Espen Espelund)
* Add sponsorship message
* General cleanups to _process_login.php

= 2.0.4 (2011-06-09) =
* Add a channelUrl to FB.init to resolve [known bugs](https://developers.facebook.com/docs/reference/javascript/FB.init/) with the FB api

= 2.0.3 (2011-06-09) =
* _process_login will now look for "rememberme" POST variable
* Added a new "wpfb_rememberme" filter, so you can override the above if desired

= 2.0.2 (2011-05-26) =
* Oops: wpfb_userinfo_permissions was redundant; removed :)

= 2.0.1 (2011-05-26) =
* Handle relative paths in usermeta (for cached avatars)
* Get rid of some depreciated functions (get_usermeta -> get_user_meta)
* Add a new hook wpfb_add_to_asyncinit, so you can output your own JS after the Facebook API initializes
* Add a new filter wpfb_userinfo_permissions, so you can choose what userinfo permissions to ask for
* Check for function_exists('is_multisite') to support older versions of WP
* More descriptive error message for "Nonce check failed."
* More descriptive error message for "Failed to get the Facebook session."

= 2.0.0 (2011-05-19) =
* As Facebook has decided to shut off the old REST API on Sept 1, 2011, I've rewritten the core plugin to use the new Graph API.  All Premium users must also update their addons to be compatible with this new core plugin.
* Removed "IE9 compatability mode" as it's no longer relevant.
* Removed "Request and require email permissions" as it's no longer relevant (all permissions are requested in a single popup, so one cannot be denied while approving the others).
* Show a warning to Premium users with an outdated version of the addon. 

= 1.9.2 (2011-04-02) =
* Add an "IE compatability mode", so the old API will work on IE9.  Can be disabled via debug options, but is enabled by default.

= 1.9.1 (2011-04-01) =
* CSS id fbLoginButton is now class fbLoginButton, to fix validation issue if multiple buttons are placed on the same page
* NOTE: Premium users using the "ajax spinner" feature must also update their addon!

= 1.9.0 (2011-04-01) =
* jfb_output_facebook_callback() is now automatically called by wp_footer; If you're manually outputting your own Facebook buttons, you should now ONLY call jfb_output_facebook_btn() (explicitly calling jfb_output_facebook_callback() is no longer needed!)
* Premium comment-form buttons now not dependent on Widget buttons
* Output some html comments

= 1.8.9 (2011-04-01) =
* Rename some functions that weren't following convention
* jfb_output_facebook_callback() prevents itself from outputting duplicate forms on the same page

= 1.8.8 (2011-03-31) =
* Just some revisions to the admin panel

= 1.8.7 (2011-03-31) =
* Another Facebook API error check in _process_login.php
* New filter wpfb_inserting_user to replace wpfb_insert_user
* CSS for the admin panel
* Slightly reworded disclaimer

= 1.8.6 (2011-03-29) =
* Remove Donate section from the admin panel (a bit redundant now that I've got a premium addon)
* Two minor html fixes in the admin panel
* Minor bug fix in browser detection (used by logging)
* Hide the MOD REWRITE section from the admin panel, and update documentation in _autologin.php

= 1.8.5 (2011-03-24) =
* Add a new wpfb_extended_permissions filter

= 1.8.4 (2011-03-22) =
* Report Browser and OS in the login logs

= 1.8.3 (2011-03-22) =
* Allow the Premium addon to reside outside the plugin dir, so it doesn't get overwritten by automatic updates (also requires an update to Premium.php; on its way...)

= 1.8.2 (2011-03-19) =
* Differentiate the "Save" buttons in the admin panel, for clarity
* Include the sitename in emailed login logs (helpful for people who admin multiple sites)

= 1.8.1 (2011-03-19) =
* Exception handling for stream.publish (may fail if the user enters too long a message)

= 1.8.0 (2011-03-19) =
* Add support for the new OpenGraph API to _process_login.php

= 1.7.3 (2011-03-18) =
* Earlier check for PHP5 in _process_login.php
* Remove extraneous test from _process_login.php
* Bundle new Facebook API (not used YET...)

= 1.7.2 (2011-03-18) =
* Cleanups to the admin panel
* Marked as compatible up to 3.1

= 1.7.1 (2011-03-15) =
* Add ability to enter your own logging email address
* Get rid of old "hide facebook button" debug option

= 1.7.0 (2011-03-01) =
* Fix for Facebook users who've enabled "Secure Browsing (https)" on their accounts

= 1.6.9 (2011-02-10) =
* Replace depreciated update_usermeta() with update_user_meta()
* Check for completely non-alphanumeric Facebook names when autoregistering with "Pretty Names" enabled

= 1.6.8 (2011-02-06) =
* Fix validation issue if present with Wordbooker (duplicate attribute in html tag)
* Update tested compatibility to 3.0.4

= 1.6.7 (2011-02-05) =
* Fix bug with avatars on author page

= 1.6.6 (2011-01-28) =
* Reveal new premium options in the panel

= 1.6.5 (2011-01-28) =
* Add wpfb_output_facebook_locale action

= 1.6.4 (2011-01-28) =
* Add wpfb_login_rejected filter
* Add some resources for a new premium feature, & reveal more premium options in the admin panel

= 1.6.3 (2011-01-28) =
* Fixed a BP bug introduced in 1.6.2...sorry!
* Add action wpfb_after_button

= 1.6.2 (2011-01-27) =
* "Use Facebook profile pictures as avatars is now just one option" (they aren't separate for WP and BP)

= 1.6.1 (2011-01-27) =
* Fixed a bug with author links (they didn't work because the "nicename" had a space in it)
* Removed the "Enable BuddyPress Support" option; it's always enabled now
* NEW OPTION: You can now select the autoregistered username style (FB_12345, FB_John_Smith, or John.Smith)

= 1.6.0 (2011-01-23) =
* Reveal the Premium options in the admin panel

= 1.5.8 (2011-01-07) =
* Error handling for depreciated connect.registerUsers function

= 1.5.7 (2010-12-13) =
* Compatability fix for W3-Total-Cache

= 1.5.6 (2010-11-24) =
* Remove one unnecessary call to Facebook API
* Add wpfb_admin_messages action
* Pass the callback name to wpfb_add_to_js action

= 1.5.5 (2010-11-23) =
* Add support for a new option in the premium version
* More descriptive error message
* Add wpfb_existing_user action

= 1.5.4 (2010-11-03) =
* jfb_output_facebook_init() is output in footer, once, instead of using jQuery.  Should resolve conflict if multiple buttons are used on the same page.

= 1.5.3 (2010-11-02) =
* Slight revisions to readme
* Remove unneeded debug code

= 1.5.2 (2010-11-01) =
* Added new wpfb_prelogin action
* Added new wpfb_submit_loginfrm filter
* Added new wpfb_output_button filter
* Cleaner handling of a few admin panel options

= 1.5.1 (2010-11-01) =
* Cleaner integration with Premium addon

= 1.5.0 (2010-10-31) =
* Add full support for the Premium add-on
* Revise the features list in the Readme

= 1.4.4 (2010-10-30) =
* The wpfb_inserted_user action now supplies the full userdata of the inserted user
* Don't initialize the Facebook button until the page has finished loading (can be disabled via param to jfb_output_facebook_init())
* Setup hooks & options for lots of new premium features
* Add return URL to paypal donate button

= 1.4.3 (2010-10-29) =
* Hide the main plugin options until a valid API Key and Secret have been entered.

= 1.4.2 (2010-10-29) =
* Cleaned up admin panel code, regrouped the options, and rephrased some sections for better clarity. 
* Cleaned up BuddyPress & Avatar code a bit
* Add an optional "Powered By" link (defaults to off)
* Revisions to premium-checking code

= 1.4.1 (2010-10-29) =
* Remove unneeded debug code
* Add support for eventual premium functionality 

= 1.4.0 (2010-10-27) =
* Handle users with non-alphanumeric characters in their Facebook names.
* Use Firstname.Lastname rather than FirstnameLastname for Buddypress logins
* Revised some debug code, fixed problem with get_plugins()

= 1.3.14 (2010-10-26) =
* When debug logging is enabled, show REQUEST variables
* Added 2 new actions: wpfb_add_to_js and wpfb_add_to_form (Sponsored by [VideoUserManuals](http://9f200kliq7f39zam4ffc7wnk8b.hop.clickbank.net/))

= 1.3.13 (2010-10-26) =
* The prompts "Ask for permission to get the connecting user's email address" and "Request permission to post to the user's wall" are split into 2 separate permissions dialog, so the user may accept one but deny the other. (Sponsored by [VideoUserManuals](http://9f200kliq7f39zam4ffc7wnk8b.hop.clickbank.net/))

= 1.3.12 (2010-10-14) =
* Update the instructions (Facebook has changed some of the settings on their Create Application script).

= 1.3.11 (2010-10-14) =
* Performance optimization when searching for existing users during a login (thanks to Andy Clark)

= 1.3.10 (2010-08-31) =
* Still more checks to try and pinpoint the elusive "nonce check failed" bug

= 1.3.9 (2010-08-29) =
* More detailed log message on "nonce check failed" (to try and figure out what's causing it)

= 1.3.7 (2010-08-28) =
* Add a simple check to prevent users from accessing _process_login.php directly, PRIOR to the nonce check (so they get a different and more accurate error message)

= 1.3.5 (2010-08-24) =
* Attempt to find the user by directly looking up their email address before resorting to hashes
* Don't abort the login if Facebook refuses to register hashes (relevant on blogs with over 3,000 users)

= 1.3.4 (2010-08-23) =
* Slight rewording in the admin panel, for clarity
* Store proxied emails, if selected (Previously, the plugin was erroneously treating a "proxied facebook address" as "email address denied"; the log will now show what's really going on, and will store a proxied address, if selected).

= 1.3.3 (2010-08-23) =
* Clear previously fetched avatar if Facebook user has removed their profile picture
* Marked as compatible up to 3.0.1 (Oops! Forgot to do this earlier.)
* Nicer error reporting (thanks Andy Clark)

= 1.3.2 (2010-08-15) =
* Do not fetch Facebook profile picture if not present (revert to default WP/BP avatar)

= 1.3.1 (2010-08-14) =
* Fixed the "Object of class WP_Error could not be converted to string" bug

= 1.3.0 (2010-08-08) =
* Update Facebook API; PHP5 is now the minimum requirement
* This should (hopefully) fix the conflict with newer OpenGraph plugins (i.e. Like Button)

= 1.2.5 (2010-08-08) =
* New Feature: Use Facebook profile pictures as Wordpress avatars
* Code reorganization; BuddyPress code is now in Main.php, avatars are fetched in _process_login.php, etc.

= 1.2.4 (2010-08-07) =
* Reorganize options a bit to make a separate "Buddypress" section
* Made "Replace BuddyPress avatars with Facebook profile pictures" as optional
* Use htmlspecialchars so the widget will validate when redirect_to contains special chars

= 1.2.3 (2010-08-04) =
* Get rid of PHP short tags

= 1.2.2 (2010-07-24) =
* Added "Disable nonce check" to debug options (not recommended - see FAQS on the plugin page) 

= 1.2.1 (2010-07-14) =
* Oops! I made a commit error in 1.2.0.

= 1.2.0 (2010-07-14) =
* BuddyPress usernames generated via "First Name + Last Name" instead of "Name" (as reported [here](https://www.justin-klein.com/projects/wp-fb-autoconnect/comment-page-6#comment-12258))
* Facebook profile images are automatically displayed as BuddyPress avatars

= 1.1.9 (2010-05-28) =
* Again redo how the "Require Email" option is enforced
* Add option to publish new user registration announcement on user's walls (prompts for permission on connect)

= 1.1.8 (2010-05-17) =
* Added action wpfb_inserted_user to run *after* a user is inserted
* Fixed "Require Email" option

= 1.1.7 (2010-04-11) =
* Minor change: Use wp_generate_password() for autogenerated passwords

= 1.1.6 (2010-03-28) =
* Fixed to work on sites with over 1,000 existing users.

= 1.1.5 (2010-03-23) =
* Add an error check for a very rare bug; If the plugin is working on your site, you may skip this upgrade. 

= 1.1.4 (2010-03-23) =
* Include version number in login logs
* Slightly more descriptive error message in login logs
* Sanitize autogenerated usernames for BuddyPress
* Add "Show full log on error" option
* Add "Remove All Settings" (uninstall) option

= 1.1.3 (2010-03-22) =
* Check if other plugins have already included the Facebook API

= 1.1.2 (2010-03-21) =
* Logging: On failure, show the accumulated log up to the point of failure
* Logging: Show REQUEST variables
* Main: Add optional params to jfb_output_facebook_callback() and jfb_output_facebook_instapopup() so the default callback name can be overridden, allowing multiple login-handlers with different redirects and different email policies
* Main: auto-submitted login form's name based on the js callback name, to support multiple handlers
* Autologin: Fixed issue if both a button an autopopup were on the same page
* Include license

= 1.1.1 (2010-03-19) =
* Hopefully fix a crash on sites with more than 1,000 existing users
* Fix bug on some PHP4 configurations

= 1.1.0 (2010-03-18) =
* BuddyPress option is automatically enabled for BP installations
* Add wpfb_insert_user filter to run just before inserting an auto-created user
* Improved support for BuddyPress: use "pretty" usernames to fix profile links
* Include client IP in connection logs
* Cleanups/revisions to connection logs

= 1.0.8 (2010-03-18) =
* Add option to include Buddypress-specific filters
* Cleanup the Admin panel & update documentation

= 1.0.7 (2010-03-17) =
* Fix email hash-lookup for blogs with over 1,000 existing users

= 1.0.6 (2010-03-17) =
* Oops - Add support for PHP4 (really this time)

= 1.0.5 (2010-03-17) =
* Add support for PHP4

= 1.0.4 (2010-03-17) =
* Include the Facebook javascript in jfb_output_facebook_init() instead of wp_head
* Redirect form not generated by JS (this was leftover from an older version of the plugin...)
* Only check email hashes if there are actually existing users on the blog 
* Add wpfb_connect hook that runs BEFORE a login is allowed
* If email privilege is denied on first connect, but subsequently allowed, the user's auto-generated account will have its email updated to the correct one.
* Added uption to REQUIRE email address (not just prompt for it)
* XHTML Validation fix
* Small typo in the Widget

= 1.0.3 (2010-03-16) =
* Hopefully fix the "Call to undefined function wp_insert_user()" bug

= 1.0.2 (2010-03-16) =
* Fix API_Key validation check - should work properly now.

= 1.0.1 (2010-03-16) =
* Convert PHP short tags to long tags for server compatability

= 1.0.0 (2010-03-16) =
* First Release


== Support ==

Please direct all support requests [here](https://www.justin-klein.com/projects/wp-fb-autoconnect#feedback)