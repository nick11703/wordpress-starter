# wordpress-starter
Simple WordPress starter that separates plugins and themes from the core file set.This allow for easily swapping WordPress version for testing.

## Requirements

1. Apache server with .htaccess override enabled
2. A copy of your favorite WordPress version

## Installation

1. Download and copy to the root folder of your site.
2. Download and paste your copy of WordPress into the __wordpress__ folder
3. Navigate to the root directory in your browser. No need to include the __wordpress__ directory. The .htaccess file to handle the proper redirects

## Expanding

If you would like to include additional versions of WordPress for testing, create additional folders at the same level as the __wordpress__ folder. One folder foe each versions of WordPress. To change whack version is used, edit the __.htaccess__ file and change line ten.

`[E=WP_FOLDER:wordpress]` Change wordpress to the folder of your choice.


