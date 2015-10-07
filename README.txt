webClinic Pro
https://www.webclinicpro.com

Configuration
------------------------------------------------------------------------------

Do not use on development environments/servers the functionality of this 
module was built for production environments online.  Before installing
verify that your website works via https.

This module requires a subscription with webClinic Pro.  Please do not use
unless you have a subscription first.  Each subscriber will be authenticated
by their domain and a subscriber key.  Please contact a webClinic Pro
Representative if you do not know or have lost your key.

Removal of web
------------------------------------------------------------------------------

To override Forced SSL add the following line to settings.php

$conf['webclinicpro_forced_ssl'] = 0;

In the case where your SSL mode has been disabled and you can no longer access
the administration section of your site to disable the module you can do one
of the 2 following things.

  1. Use the above method to disable the module.
  2. delete the module from your site.

If you can use the first option but if you can't edit your settings.php then
deleting it will not break your site, but will leave some variables that are
set by the module.

Thanks
------------------------------------------------------------------------------
Special thanks to all the contributors for Secure Pages: gordon, nagba, grendzy,
pineray, and dww.  These module used the code from Secure Pages as a starting 
point for forced ssl.