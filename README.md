# WP Sane Setup

Make some sensible setup changes to a new WordPress installation.

## Changes WP Sane Setup will make to your fresh install:

 - Delete the 'Hello World' post
 - Delete the 'Sample' page
 - Create a 'Home' page
 - Set the front page to 'Home'
 - Rename the 'Ucategorized' category to 'News'
 - Set the start of the week to Monday
 - Set default permalinks to `/category/post-name`
 - Disable emojis

## UI

Once the plugin is enabled, a WordPress admin notice will ask you to run sane setup:

![Admin Notice](http://i.imgur.com/7WlNsJi.png)

Once the WP Sane Setup has run, the plugin is rundundant, and an admin notice will ask you to deactivate the plugin. After this you may want to delete WP Sane Setup from your plugins.

![Done Admin Notice](http://i.imgur.com/uIGky3u.png)

## Contributing

Contributions for other 'sane defaults' are welcome. Send me a pull request!

It's pretty easy, just wrap the singular change you want to make in a function, then in `function do_setup()`, call  `$this->example_change();`.
