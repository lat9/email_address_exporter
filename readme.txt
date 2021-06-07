Add-On: Email Address Exporter Admin Tool
Designed for: Zen Cart v1.5.6+ 

Created by: DrByte
Some revisions added by: Swifty8078, Ooba_Scott, That Software Guy and lat9

Donations:  Please support ZenCart!  paypal@zen-cart.com  - Thank you!
===========================================================

NOTES:
This add-on was created to allow quick and easy exporting of email addresses from your Zen Cart shop.

This is especially useful if you are needing to manage mailing lists and/or send newsletters or mass-emailings from your personal computer.
One great tool to use this with is GroupMail, which you can get a free copy of here: http://www.shareasale.com/r.cfm?B=3937&U=151719&M=1465

As to export formats, you can choose from CSV, TXT (tab-delimited), XML, or HTML formats.

You can select any of the audiences available in your cart, using the pulldown menu provided.
The most common audience would be Newsletter recipients.

If you choose the "Save To File On Server" option, the file created is saved in the admin's /backups folder, which must be
writeable.  When saving to file, if a file of the same name already exists, it will be overwritten.

===========================================================

INSTALLATION:  
Upload all files as-is to your server, retaining folder structures, i.e. after unzipping this file you have an "admin" folder on your PC, with several folders/files in it. On your server you also have an "admin" folder (perhaps renamed to something else for security). Simply upload the files from your PC's "admin" folder to your server's (renamed) "admin" folder, putting files into the same folders on the server as you find them on your PC.

In your Admin permissions panel, grant access to appropriate users using the Admin Access Management screen.

===========================================================

USE:
To use, just log into the admin area, click on "Tools", and click on "Export Email Addresses".

===========================================================

HISTORY:
March 10/05 - Initial Release
April 15/05 - Added XML format
May 11/05   - Added Save To File format, and tweaked streaming methods slightly
July 2012 - updated for Zen Cart v1.5.0
Sept 2012 - DrByte updated for Zen Cart v1.5.1, and to add ability to easily add more fields to the output, along with THREE-STEPS INSTRUCTIONS in the code on how to do it.
Nov 2013 - DrByte added a fix to prevent a database error from occurring when you forget to choose an export option
Dec 2013 - DrByte removed debug code left in previous update.
Dec 2014 - tidying
Aug 2017 - included telphone and company fields in export (requires them to be in the db query that feeds the exporter though). Also forced limits on filenames used for exporting.
20210607-lat9, v1.5.6a
    - Removed /admin/boxes (pre-zc15x use only).
    - Output file now saved in /admin/backups