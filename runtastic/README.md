Runtastic mass exporter
=======================

Allows exporting many workouts from [Runstastic](http://www.runtastic.com/)
website by single click.


How to use
----------

You need [Firefox](https://www.mozilla.org/en-US/firefox/all/) web browser with 
[Greasemonkey addon](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) 
installed.

Then you can install this script from [userscripts.org](https://userscripts.org/) or
[download it from GitHub](https://github.com/barszczmm/greasemonkey-scripts/raw/master/runtastic/Runtastic_mass_exporter.user.js)
and drag it to your browser window.
 
When script is installed go to [runtastic.com](http://www.runtastic.com) and 
**set language to English** at the bottom of the page (if it is not set to 
English already). Setting website language to English is very important - script 
will not work if other language is set.

Now click on *Activities* tab. You should see list of activities from current 
month. At the top of the month table there should be new orange button labeled 
*Export This Workouts*. This button allows exporting all workouts from currently 
selected month.
![screenshot-2](https://raw.github.com/barszczmm/greasemonkey-scripts/master/runtastic/screenshot-2.png)

You can also export all workouts from currently selected year.
![screenshot-1](https://raw.github.com/barszczmm/greasemonkey-scripts/master/runtastic/screenshot-1.png)

When you click on the *Export This Workouts* button you should see modal window 
with options to choose exported files format (gpx, tcx or kml) and info about 
needed browser configuration.
![screenshot-3](https://raw.github.com/barszczmm/greasemonkey-scripts/master/runtastic/screenshot-3.png)

**Very important step before starting export:** you have to configure your 
browser to automatically save files of chosen type (with chosen extension). You 
can do it by trying to download one of that files and when your browser asks you 
what to do, select *Save file* and check *Remember for this type of files* 
(texts in your browser may be slightly different but they should mean the same).

When everything is configured you can click *Export* and script will start to 
download each file with 2 seconds interval.



