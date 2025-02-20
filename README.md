﻿# Inpsyde Multisite Feed

[![Latest Stable Version](https://poser.pugx.org/inpsyde/WP-Multisite-Feed/version)](https://packagist.org/packages/inpsyde/WP-Multisite-Feed)
[![Build Status](https://travis-ci.org/inpsyde/WP-Multisite-Feed.svg?branch=master)](https://travis-ci.org/inpsyde/WP-Multisite-Feed)

Consolidates all network feeds into one on https://www.remedylist.com.

## Description
Create a separate feed for your whole multisite. This feed will have a custom url. You can limit the number of entries per blog and the maximum number of entries for the whole feed.

## Installation
### Requirements
 * PHP 5.6
 * WordPress version 3.3 and later (tested with version 5.1)

### Installation
 1. Upload the plugin directory to the `/wp-content/plugins/` directory or use the installer via backend of WordPress. Also it is possible to use as [Must Use plugin](https://codex.wordpress.org/Must_Use_Plugins).
 1. Activate the plugin through the 'Plugins' menu in WordPress in the Network Admin
 1. Configure it in Settings > MultiSite Feed

## Screenshots
 1. [Settings](https://github.com/inpsyde/WP-Multisite-Feed/blob/master/w-org-assets/screenshot-1.png)

## Other Notes
### Bugs, technical hints or contribute
Please give us feedback, contribute and file technical bugs on this [GitHub Repo](https://github.com/inpsyde/WP-Multisite-Feed), use Issues.

### Available Filter Hooks
 * `rss_update_period` - Update period, global filter from WordPress Core; works on all RSS feeds
 * `rss_update_frequency` - Update frequency,  global filter from WordPress Core; works on all RSS feeds
 * `inpsmf_feed_url` - Filter feed url, on default use the slug of plugin settings
 * `inpsmf_feed_title` - Filter the feed title
 * `inpsmf_feed_description` - Filter feed description

### Available Action Hooks
 * `rss2_ns` - Runs inside the root XML element in an RSS 2 feed (to add namespaces). It is an core hook, works on all feeds.
 * `rss2_head` - Runs just after the blog information has been printed in an RSS 2 feed, just before the first entry. It is an core hook, works on all feeds.
 * `rss2_item` - Runs just after the entry information has been printed (but before closing the item tag) for each blog entry in an RSS 2 feed. It is an core hook, works on all feeds.

### Made by [Inpsyde](https://inpsyde.com) &middot; We love WordPress
Take a look at [our website](https://inpsyde.com/) if you like to get to know us.

### Authors, Contributors
 * [Eric](https://github.com/eteubert)
 * [Frank](https://github.com/bueltge)
 * [Moritz](https://github.com/Biont)

### License
Good news, this plugin is free for everyone! Since it's released under the GPL, you can use it free of charge on your personal or commercial blog. But if you enjoy this plugin, you can thank me.

### Translations
The plugin comes with various translations, please refer to the [WordPress Codex](http://codex.wordpress.org/Installing_WordPress_in_Your_Language "Installing WordPress in Your Language") for more information about activating the translation.

### Contact & Feedback
The plugin is designed and developed by the team of [Inpsyde GmbH](https://inpsyde.com)

Please let us know if you like the plugin or you hate it or whatever ... Please fork it, add an issue for ideas and bugs.

## Changelog

 * [see CHANGELOG file](CHANGELOG.md)
