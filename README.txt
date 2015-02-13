Responsive Blocks
=============

This is a lightweight solution for responsive blocks based on the 
MediaCheck library.
(http://sparkbox.github.io/mediaCheck/) 

This module is intended to aid Developer's and Designer's when 
working on Responsive design.

Requirements
------------

As noted, this module does not include the actual mediaCheck library. 
This should be downloaded or cloned from one of the links above and 
placed in 

 - sites/all/libraries/mediaCheck

or somewhere the Libraries API (if present) can find it, eg

 - sites/default/libraries/mediaCheck
 - sites/example.com/libraries/mediaCheck
 
Once the module is installed and enabled, browse to the Status Report 
page (admin/reports/status) and confirm that the library is found. The 
PHP file should have a pathname that is similar to 

 - sites/all/libraries/mediaCheck/mediaCheck.js
 
If you think everything is installed correctly, you may need to clear 
the Drupal caches (admin/config/development/performance). 



Usage
-----

This module provies an interface to Developer's/ Designer's to select
and confirm if block should be 
displayed for particular device.

Future
------

TO DO : 
   Add options to add new Devices/Resolutions.
