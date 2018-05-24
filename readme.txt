=== Surbma - GDPR Proof Cookies ===
Contributors: Surbma
Donate link: https://surbma.com/donate/
Tags: gdpr, analytics, google analytics, popup, cookie, cookie compliance, cookie law, cookies, eu cookie, facebook, facebook pixel, hotjar
Requires at least: 4.6
Tested up to: 4.9
Requires PHP: 5.6
Stable tag: 11.2
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

This plugin helps your website to comply with GDPR cookie regulations by asking every visitors to accept or decline cookie tracking.

== Description ==

>USE **BEFOREGDPR** COUPON CODE FOR 50% OFF FROM YOUR FIRST PURCHASE TILL MAY 26, 2018!

This plugin helps your website to comply with GDPR cookie regulations by asking every visitors to accept or decline cookie tracking. If visitor choose to decline, than no visitor data will be sent to third party services. If visitor accepts tracking, than data will be sent to third parties. So visitors can choose to be tracked or not, before they visit any page of the website.

This plugin can be used as a simple Cookie Policy plugin, if you don't have any tracking or marketing cookies on your website. Simple and beautiful solution for all websites.

The Surbma - GDPR Proof Cookies plugin is born from my original Surbma - GDPR Proof Google Analytics plugin. It is now supporting only Google Analytics tracking, but it will soon support Facebook Pixel, Google Remarketing, HotJar and other popular services also. It will even support custom codes also.

The cookie saved by this plugin is not storing any sensitive personal data, it is storing only two fix values: "yes" or "no". This cookie management is GDPR proof, as it is impossible to identify any user with the cookie data. Cookies will expire in 30 days by default.

### Limited Liability

>This plugin does not substitute any legal adequacy. Texts, that are displayed in the popup is edited by the user of this plugin and I do not take any responsibility regarding GDPR adequacy or change.

### Free version features

- Simple Cookie Policy popup
- Hide Decline button
- Cookie Scan page
- Live Cookie Scan shortcode
- Cookie settings link with shortcode
- Cookie Policy
- Developer Friendly
- WPML & Polylang Compatible

### Additional features in the Pro version

- Snackbar before Popup
- 6 positions for Snackbar
- Full Customizations
- Cookie Policy Link
- Themes
- Full Cookie Control
- Google Analytics IP Anonymization
- Google Analytics Tracking Code Customizations

### Features in details

#### Simple Cookie Policy popup
If you don't have such cookies on your website, that need visitor consent, you can use this plugin as a simple Cookie Policy popup, so you can inform your visitors about the cookies you use. It will show your informations in a beautiful popup and a link to your Cookie Policy page.

#### Hide Decline button
If you only want to show the Accept button, you can hide the Decline button.

#### Cookie Scan page
This page will display all the saved cookies for you, so you can see, what cookies are used in your website.

#### Live Cookie Scan shortcode
You can display all the actual Cookies, a visitor has right now. It is not a full list of Cookies, that your website is using!

This is the shortcode: `[surbma-live-cookie-scan]`

**It has 1 attribute:**

cookievalue - Show or hide the Cookie values in the list.

**Example:**

    `[surbma-live-cookie-scan cookievalue="false"]`

#### Cookie Settings Link
There is a shortcode, that will place a link in your content. Clicking on the link will open the Cookie Popup again, and users can change their settings about the Cookie trackings.

This is the shortcode: `[surbma-cookie-popup-link]`

**It has 2 attributes:**

class - You can set the class of the link, so you can easily create a button like link.
text - You can change the default text of the link, which is "Open Cookie Settings".

**Examples:**

    `[surbma-cookie-popup-link text="I've changed my mind about Cookie settings."]`
    `[surbma-cookie-popup-link class="button" text="Please show me the Cookie settings again!"]`

#### Cookie Policy
Set your Cookie Policy page, where the popup won't load for visitors. Cookie tracking codes are not loading on this page!

#### Developer Friendly
If you enable debug mode, popup will show always, on every refresh, so you can test how it works.

#### WPML & Polylang Compatible
If you have a multilingual website, you can set the texts for each language with WPML String Translation add-on.

#### Snackbar before Popup
Modest Snackbar before Popup display, so the first time is not that aggressive. The link in the Snackbar opens the Popup. Choose between 6 positions to show the Snackbar.

#### Full Customizations
Every text is customizable, even the button's texts! You can also set the design of the buttons.

#### Cookie Policy Link
Show your Cookie Policy page link in the popup.

#### Themes
There are popup themes to choose the design, you like. The Full Page Themes are hiding the entire content behind the popup. There are a lot of design settings to make the popup fit your website design. Dark mode is also available.

#### Full Cookie Control
Set cookie expiration for visitors, so the popup won't show again in X days, you set.

#### Google Analytics IP Anonymization
You might need to disable IP Anonymization of the hit sent to Google Analytics. This setting is active by default to ensure the maximum GDPR compliance, but you can disable this option.

#### Google Analytics Tracking Code Customizations
Choose between gtag.js framework or analytics.js library. You can also set, if you want to track logged in users or the admin area.

### About Surbma

#### You can find my other plugins and projects on GitHub

[https://github.com/Surbma](https://github.com/Surbma)

Please feel free to contribute, help or recommend any new features for my plugins, themes and other projects.

#### Do you want to know more about me?

Visit my webpage: [Surbma.com](https://surbma.com/)

#### Do you like and use my free plugins?

You can donate me for FREE here: [Surbma.com](https://surbma.com/donate/)

== Installation ==

1. Upload `surbma-gdpr-proof-google-analytics` folder to the `/wp-content/plugins/` directory
2. Activate the Surbma - GDPR Proof Cookies plugin through the 'Plugins' menu in WordPress
3. Go to settings page: Settings -> GDPR Proof Cookies
4. Set the Popup content, display options, tracking code settings and approve the Limited Liability option.
5. That's it. :)

== Frequently Asked Questions ==

= Is it really GDPR compatible? =

This plugin shows a simple popup for every new visitors with two options: accept or decline the cookie tracking. If the visitor declines tracking, cookie tracking codes won't activate. This plugin gives you all the tools to make your cookie tracking GDPR proof, but it is your responsibility to use it the right way.

= What does Surbma mean? =

It is the reverse version of my last name. ;)

== Changelog ==

= 11.2 =

- FIX - Pro features are enabled for trial users also. Sorry!

= 11.1 =

- FIX - Shame on me, new Snackbar didn't see the surbma_gpga cookie. Now it works as expected.

= 11.0 =

- PRO - The long awaited and much requested Snackbar is HERE!
- NEW - Documentation menu with shortcode descriptions and how-tos.
- ENHANCED - Minor changes in admin styles.
- ENHANCED - Minor description changes.

= 10.0 =

- NEW - Shortcode to show the actual Cookies for visitors: [surbma-live-cookie-scan]
- NEW - Hide Decline button, if you don't want to show it.
- PRO - 7 days trial can be selected to try all PRO features.

= 9.1 =

- FIX - Cookie Popup will load on Cookie Policy page with the [surbma-cookie-popup-link] shortcode.
- FIX - Popup close X button format, to prevent underline text decoration.
- ENHANCED - Google Analytics code will load on Cookie Policy page, if tracking is enabled.
- ENHANCED - The whole script is embed in the condition to load or not.

= 9.0 =

- NEW - Cookie Scan page added. This page will display all the saved cookies for you, so you can see, what cookies are used in your website.
- FIX - Some texts were not set for localization. They all fixed.

= 8.0 =

- NEW - The popup is loading now, even if no Google Analytics code has been added. So the plugin is working as a simple cookie policy popup.

= 7.2 =

- NEW - Added Cookie Policy page setting to WPML config, so you can set the page for all languages. The page ID must be used as a "translation".
- ENHANCED - Description text modified.
- FIX - Replaced old plugin names in admin area.
- FIX - Future snackbar script conflict removed.

= 7.1 =

- ENHANCED - Description text modified.

= 7.0 =

- NEW - Changed plugin name: Surbma - GDPR Proof Cookies
- This is the new version of my previous Surbma - GDPR Proof Google Analytics plugin, which will add Google Remarketing, Facebook Pixel, Hotjar and other services. It will be a complete cookie management solution for WordPress.
- NEW - Shortcode, that can be used to give users the possibility to change their settings: [surbma-cookie-popup-link]
- NEW - Upcoming features list in the sidebar to let you know the future of the plugin.
- TWEAK - Modified admin area look. Preparing for the upcoming new features.

= 6.3 =

- FIX - Fixed method to get plugin info. It was generating errors for Pro users.
- TWEAK - New UIkit version added for the admin area.

= 6.2 =

- FIX - Localization fixes.

= 6.1 =

- FIX - Show the popup, when Debug mode is enabled and popup is disabled for logged in users.

= 6.0 =

- NEW - Added popup close without clicking on the buttons: button, ESC, background click.
- NEW - Added popup delay option.
- ENHANCED - Optimized script loading logic.
- ENHANCED - ESC button close is always enabled in Debug mode.
- ENHANCED - Popup is not loading in admin area, only on login page, if admin tracking is enabled.
- TWEAK - Minor admin CSS changes.
- FIX - Corrected modal values.

= 5.1 =

- FIX - Freemius mechanism added to prevent conflicts with premium version.

= 5.0 =

- ENHANCED - Popup buttons are not refreshing the page. Accept button still sends the hit to Google Analytics.
- ENHANCED - Settings page sidebar is updated with Google's latest websites about GDPR.
- TWEAK - General admin notice is removed. A more informational alert is added to the plugin's settings page.
- FIX - Internationalization fixes.
- FIX - Admin URLs are fixed to work with every WordPress configuration.

= 4.3 =

- FIX Unique JavaScript function names to avoid conflicts with other plugins.

= 4.2 =

- FIX Settings validation error.
- ENHANCED Popup load conditions.

= 4.1 =

- FIX Freemius sandbox mode removed.

= 4.0 =

- ENHANCED Debug mode has the option to close popup with ESC or clicking on the background.
- ENHANCED A lot of code optimization.
- FIX Popup related JavaScript codes are reordered.

= 3.2 =

- FIX Localization fixes.

= 3.1 =

- FIX The Limited Liability option notice.
- FIX Text sanitization an validation.
- FIX Minor code fixes.
- CHANGED Removed Affiliate banner from sidebar.

= 3.0 =

- NEW Pro version upgrade feature is available in the plugin's admin menu. Use BEFOREGDPR coupon to get 50% off till May 26, 2018.
- ENHANCED Plugin activation hook.
- ENHANCED Code optimization for settings page.
- ENHANCED Settings page display for Free users.
- FIXED Loading logic for admin and login pages.

= 2.1 =

- Main plugin file is renamed to prepare for merging free and pro versions to one plugin.
- Fix README plugin name.

= 2.0 =

- Added Freemius service to manage premium version and payment system.
- Preparing to merge free and pro codes to one plugin.

= 1.1 =

- Top-Level Menu.
- Preparing the sidebar to have relevant informations.
- Simple versioning.

= 1.0.0 =

- Initial commit.
