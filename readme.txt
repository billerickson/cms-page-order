=== CMS Page Order ===
Contributors: billerickson
Tags: page, pages, posts, order, cms, drag-and-drop, rearrange, reorder, management, manage, admin
Requires at least: 3.1
Tested up to: 3.4.1
Stable tag: 0.3.2

Change the page order with quick and easy drag and drop.

== Description ==

Adds the ability to rearrange the pages with drag and drop.

The plugin resembles [CMS Tree Page View](http://wordpress.org/extend/plugins/cms-tree-page-view/) in many ways, but is designed to look as native as possible, to be used in client projects. There is no plugin branding or donate button. Just pure functionality.

For theme developers, there's quite a few filters in place for customizing:

`cmspo_post_types`
Specify the post types the plugin applies to ([example](http://www.billerickson.net/code/change-post-types-cms-page-order/))

`cmspo_max_levels`
The number of levels pages can be nested.

`cmspo_post_statuses`
The post statuses to show. Default: all (including custom statuses), except trash, auto-draft and inherit

`cmspo_page_label`
The label for the subpage in the admin menu ([example](http://www.billerickson.net/code/cms-page-order-customize-page-label/))

`the_title`
Standard WP filter, but can be used to customize the page names([example](http://www.billerickson.net/code/add-taxonomy-to-page-names-cms-page-order/))

#### In Short:

* Quick and easy drag and drop for rearranging of pages
* Actions: View, edit, trash and publish (drafts and pending pages)
* Set the maximum number of nesting levels
* Set the applicable post types
* Native looking
* [WPML](http://wordpress.org/extend/plugins/sitepress-multilingual-cms/) support

#### Translations

* English
* Swedish
* French (thanks to Stéphane Le Roy)

== Installation ==

1. Upload the folder `cms-page-order` to your plugin directory (usually `/wp-content/plugins/`)
2. Activate the plugin through the 'Plugins' menu in WordPress

== Screenshots ==

1. Pages displayed as a tree.
2. Filter hook to set the maximum number of nesting levels.
3. Post status labels with support for custom statuses.

== Changelog ==

= 0.3.2 = 
* Added italian translation
* Added support for WP Multisite, thanks benhuson

= 0.3.1 =
* Added 'cmspo_page_label' filter for controlling the page label.
* Updated readme with more information on available filters

= 0.3 =
* Rebuilt the contextual help to work with WordPress 3.3
* Added user capability check, so code only loads if user can edit pages.

= 0.2 = 
* Added support for custom post types. Use 'cmspo_post_types' filter. See: https://gist.github.com/1380344

= 0.1.4 =
* Added French translation by Stéphane Le Roy
* Calls the_title filter for compatibility with qTranslate (patch by Stéphane Le Roy)
* Style corrections for Wordpress 3.2

= 0.1.3 =
* Updated nestedSortable from 1.3.3 to 1.3.4: Fixes a problem with elements sometimes getting kicked out of the ol element.

= 0.1.2 =
* Fixes a problem with scheduled posts not updating the date when transitioning to publish status
* Page order number now respects depth (resets to 1 at every new level)
* Removing left and right parameters in order array
* Minified nestedSortable

= 0.1.1 =
* Fixes a problem with permalinks not updating
* Updated nestedSortable from 1.3.2 to 1.3.3

= 0.1 =
* Some functions rewritten
* Updated nestedSortable from 1.3.1 to 1.3.2
* Bug fixes

= 0.1b =
* First release.

== Localization ==

Want to contribute with a translation to your language? Contact me at cmspageorder@gmail.com.