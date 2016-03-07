##Sacramento Homeless resource mapper

**aka "Homeless resource Finder"**

###NOTICE: This is an adaptation of Tom Kompare's Chicago Flu Shot Finder

This application was developed for Sacramento County 
to help Chicago residents identify a convenient no cost CDPH flu shot event.

[http://chicagoflushots.org/](http://chicagoflushots.org/)

###BACKGROUND

###BITS AND BYTES
Evens listed here are maintained and published to a Google Fusion
Table by ???. This code uses the Google Maps API to retrieve those events. We use
Google Fusion Tables.

####The Fusion Table:
???


###CODE NOTES
This a HTML/CSS/JavaScript web application. It does have one small PHP (ical.php)
file to construct an iCal file for users who want a calendar reminder of one-off
events. This PHP file should be simple enough to rewrite in whatever server-side 
language is available in your environment.

If you want to reuse this code for your city/county/province/state, a good place
to start is in main.js and altering the properties of the "Default" object at the 
top of the file.

You probably also want to change the stuff found in the Flushots.setMapSocial
function.

I try to use meaningful variable names, so hopefully the code won't be too hard 
to follow.


###CODE REPOSITORY NOTES
I have been exceptionally terrible at organizing the code repository for Chicago Flu
Shots and it has not gotten proper love over the last few years. I plan on 
changing my ways.

You all should **expect a branch each year** with the naming 
convention of 'vYYYY-YY'. For example: 'v2015-16' for the 2015-2016 season's
round of updates. **Each's year's updates will be merged back into the 'master'
branch when development is complete.** This will generally occur in the **late 
Summer or early Autumn** every year. Smaller bug fix branches may be created
at anytime and merged back into 'master' when the bug is squashed.

###ERRATA
-- TODO -- rebadging and branding for the County of Sacramento

Kevin Fries
e: [kelfink@yahoo.com](mailto:kelfink@yahoo.com)
t: [@xelfink](//twitter.com/xelfink)
