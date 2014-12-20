## unthumbnail

###Summary
A script to delete all image files generated automatically by Wordpress.

### Overview
Whenever an image file is uploaded into Wordpress using the Media Uploader, a variety of additional image files are derived from it for use by Wordpress and various themes. These files are all named using the same nomenclature:

	<original file name>-[1 or more numbers]x[1 or more numbers].ext

The numbers that are added to the resized filename are taken from the size of the automatically generated image file, and those sizes in turn are taken from either the Media settings for Large, Medium and Thumbnail images sizes in the Media tab of the Wordpress admin or other named sizes that may be added by a theme.

This script can be used to purge old derived images and start afresh should you decide to change the media sizes for your blog.

### Notes
Must be run from a command shell in the uploads folder.

It will delete anything that matches without warning.
