=== Faust ===
Contributors: antpb, apmatthe, blakewpe, chriswiegman, claygriffiths, jasonkonen, joefusco, markkelnar, matthewguywright, mindctrl, modernnerd, rfmeier, TeresaGobble, thdespou, wpengine
Tags: faustjs, faust, headless, decoupled
Requires at least: 5.7
Tested up to: 6.2
Stable tag: 0.8.5
Requires PHP: 7.2
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Faust transforms your traditional WordPress installation into a flexible headless CMS.

== Description ==

In conjunction with the [Faust NPM packages](https://www.npmjs.com/search?q=%40faustwp), Faust enables a decoupled front-end to authenticate with WordPress through GraphQL mutations and REST API endpoints. It is the bridge between a Faust-powered front-end application, and a WordPress backend.

The plugin also provides useful options for headless sites, such as the ability to:

- Hide “theme” admin pages.
- Redirect public route requests to the front-end application.
- Rewrite WordPress URLs to front-end URLs in queried content.

== Installation ==

1. Search for the plugin in WordPress under "Plugins -> Add New".
2. Click the “Install Now” button, followed by "Activate".

That's it! For more information on getting started with headless WordPress, see [Getting Started with Faust](https://faustjs.org/docs/tutorial/dev-env-setup).

== Frequently Asked Questions ==

= If I need more support, where should I ask questions? =
Use one of the channels below to contact the Faust team for support.
[GitHub](https://github.com/wpengine/faustjs) - Faust GitHub documentation and codebase.
[Discord](https://discord.gg/J2khkF9XYK) - Interactive chat support on Discord.

= Where can I find more information about development and future features for this plugin? =

Great question! The development team posts weekly summaries of sprints related to Faust, [here](https://faustjs.org/blog).

= Why the name “Faust”? =

Johann Faust was a German printer and was instrumental in the invention of the printing press, along with his partner Johann Gutenberg. In the same way the printing press democratized the spread of information, the mission of Faust.js is to support and further the vision of WordPress to democratize publishing on the web.

== Screenshots ==

1. The settings page
2. Portfolio, blog, and basic blueprints for headless sites built with Faust
3. A code snippet

plugins/faustwp/.wordpress-org/screenshot-1.png
plugins/faustwp/.wordpress-org/screenshot-2.png
plugins/faustwp/.wordpress-org/screenshot-3.png

== Changelog ==

= 0.8.5 =

### Patch Changes

- eaa5e48: Added the `shouldShowFaustToolbar` field on the `viewer` WPGraphQL type to determine if the Faust toolbar should be shown based on user preferences.

= 0.8.4 =

### Patch Changes

- 43205e1: Bug Fix: "Post and Category URL rewrites" setting ignores protocol of configured front-end site URL

= 0.8.3 =

### Patch Changes

- c4696ef: - Added new filter `faustwp_exclude_from_public_redirect`, allowing WordPress plugins and themes to exclude certain routes from being redirected when the [enable public route redirects](https://faustjs.org/docs/faustwp/settings#enabling-public-route-redirects) setting is active.

[View the full changelog](https://faustjs.org/docs/changelog/faustwp)