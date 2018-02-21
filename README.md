# cms-inspect-and-fix

[![Build Status](https://travis-ci.org/zwiazeksyndykalistowpolski/cms-inspect-and-fix.svg?branch=master)](https://travis-ci.org/zwiazeksyndykalistowpolski/cms-inspect-and-fix)

Malware investigation tool, helps to compare files of a CMS site with a content from tar.gz/zip file or from a directory


#### Created specially for iwa-ait.org - International Workers Association pages

- http://iwa-ait.org
- http://zsp.net.pl

The case was that Drupal and Wordpress sites were often attacked and the attacked files were encrypted, so only
a backup was possible to restore. We have dozens of small information pages on Drupal and Wordpress.
In case that a smaller site has no backup made yet its the tool that helps to replace a few files without reinstalling the application.
It is also used to recover files from backup carefully, comparing the file one-by-one.
