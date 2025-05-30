# Weather34 skin for WeeWX

# Please note. This skin for WeeWX has reached end of life status. It will be maintained for bug fixes only until its successor, weewx-DivumWX, currently approaching Beta testing, achieves launch status. The new version will be called weewx-DivumWX and will be compatible with Debian 12 and the forthcoming WeeWX version 5. A demonstration of weewx-DivumWX can be seen at https://claydonsweather.org.uk. Repository at https://github.com/Millardiang/weewx-divumwx
 
# This version has only been tested with versions of Debian 11 and below. There are no guarantees that it will work with later versions of Debian, or versions of WeeWX beyond 4.10.2.

Weather Station website skin with Live Data for WeeWX. This version is compatible with WeeWX 4.x.x builds / Python 2.7 and Python 3.x. **This version of the template requires either the extended database schema introduced with WeeWX 4.0.0 or one that has been manually extended to included fields for lightning data.** It is strongly recommended that you start with an entirely new clean Python3 install of WeeWX 4.4.0 or later.

Version W34-HC-IMJD-4.3.0

Packaged for installation using its own unique installer and an online pre-installation settings form https://steepleian.github.io/weewx-Weather34

This repository contains the WeeWX version of Brian Underdown's Weather34 website template set. Brian's main website is https://weather34.com/homeweatherstation/index.html In January, 2019, Brian asked others to take over the distribution/maintainence of his design whilst he concentrated on development only for MB NanoSD, called Weather34 MB-SMART. This WeeWX version of the template is actively developed by Ian Millard and Jerry Dietrich.

The repository contains a main and development branch. To maintain integrity of the main branch, all pull request must be made via the development branch. 

This version requires WeeWX version 4.1.1 or later software. WeeWX is available at http://weewx.com. It is PHP 8 compatible.

This version is designed explicitly to harness the powerful WeeWX database to generate the weather data charts and statistical data. It was originally built on the current MB-UB40-IHVN which is now maintained by Lightmaster (Meteobridge-Weather34-Template). Although we maintain a similar look and feel with MB-UB40-IHVN,the weewx-Weather34 now has many unique features.

This version is assembled as an install package and uses its own unique installer and un-installer utilities. This greatly simplifies the installation process from that of previous versions. Depending on your own WeeWX setup, minor edits may be required to be made to weewx.conf and Weather34 skin.conf files. Please see the Weather34 skin Installation Guide for detailed instructions.

# What's New in this Version W34-4.3.0

DarkSky has been removed as a source of forecasting data etc - the API has been withdrawn by its owners Apple.

AerisWeather is now included and is the default forecasting, alerts and current conditions data source. A free developers subscribtion is required via the link in the install instructions. Weather Underground is also included as an alternative source but it does not supply the same level of data via its API.

The services.txt generating form has been updated with an improved interface, thanks to User Stephen.

With newer versions of Python3.x several fixes have add to be applied. Thanks once again to Jerry Dietrich in keeping us on track with the changes and fixes.

There are one or two other features included at the suggestion of User Sean, so thanks to him as well.

The default symbol set is now based on the yr.no symbols. (Please note that Weather Underground still uses the old set for forecasts).

Significant update of settings page.

Compliant with WeeWX 4.7.0 for remote syncrinisation. Thanks to Jerry (and to Chris for raising the issue).

Various bugs squashed. Thanks to mutiple users support in raising issues.

# Demo

A live example of Weather34 WeeWX skin can be seen at https://claydonsweather.org.uk

# Weather34 Historic Timeline of design 2014-2019 
https://weather34.com/homeweatherstation/weather34timeline/weather34timeline.html

# Template Screenshots

**Dark Theme**

![image](https://user-images.githubusercontent.com/18438654/86633765-fb60a200-bfc8-11ea-99dc-f8dc8de56e8c.png)

**Light Theme**

![image](https://user-images.githubusercontent.com/18438654/86635273-c8b7a900-bfca-11ea-9efd-76962364c2fd.png)

**Pop Up Chart - Dark Theme**

![image](https://user-images.githubusercontent.com/18438654/86635575-277d2280-bfcb-11ea-9452-e7acd7f44e62.png)

**Pop Up Chart - Light Theme

![image](https://user-images.githubusercontent.com/18438654/86636143-dae61700-bfcb-11ea-966d-4db7b487033f.png)

**Pop Up AQI Info**

![image](https://user-images.githubusercontent.com/18438654/86636425-2c8ea180-bfcc-11ea-957d-72c1180f44fb.png)

**Pop UP Alerts**

![image](https://user-images.githubusercontent.com/18438654/86637661-da4e8000-bfcd-11ea-8df6-1f872a6bb6ed.png)

**Radial Charts**

![Untitled](https://user-images.githubusercontent.com/18438654/86875356-34d50280-c0da-11ea-9b39-33acd451eb46.png)

**Hays Charts**

![image](https://user-images.githubusercontent.com/18438654/86639506-e25bef00-bfd0-11ea-9da3-043d2a640b46.png)


# Setup

**If you are upgrading from a previous version of this skin, due to the significant changes, you must recreate your settings1.php file by running the full install process. Just copying your previous settings1.php will cause errors which are then more difficult to resolve.**

Follow the instructions in the 'installation guide' (INSTALLATION_GUIDE.md) to install the template.
Browse to http://your/path/to/weewx/weather34/templateSetup.php
There is no initial password when the page prompts the first time -- just press LOGIN to enter the page.
IMPORTANT set a password in the screen for future use -- your browser can remember it. This will make future updates    reasonably secure so only you can do the updates to the configuration.
Make setting entries in the templateSetup.php page and SAVE. The next time you run it, use the password you set in the step above.
Repeat running templateSetup.php until the main screen appears as you like it.

# License

Copyright (c) 2016-2019 by Brian Underdown (https://weather34.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Template”), to deal in the Template without restriction, including without limitation the rights to, can use, can not copy without prior permission, can modify for personal use, can use and publish for personal use ,can not distribute without prior permission, can not sublicense without prior permission, and can not sell copies of the Template, and subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Template.

THE TEMPLATE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE TEMPLATE OR THE USE OR OTHER DEALINGS IN THE TEMPLATE.

Attribution-NonCommercial 4.0 International based on a work at https://weather34.com/homeweatherstation
Non-weeWX versions Available

# An Excerpt from Meteobridge-Weather34-Template MB-UB40-RRW README.md
Github repository for the Meteobridge version of the original weather34 template 
Weather Template for Meteobridge users only 

# This work is not permitted to be used in any other versions without prior permission unless listed below 
# Permission is granted for use in Cumulus version maintained by Ken True 
# Permission is granted for use in Weewx version maintained by Ian Millard

*This work means CSS/SVG/PHP .

Meteobridge Version available via download maintained by Lightmaster (https://github.com/lightmaster/Meteobridge-Weather34-Template)

Cumulus Version available via download and more info supported by Ken True ( https://github.com/ktrue/CU-HWS ). This version now also supports WeeWX and WeatherCat

# Credits for this version

Apart from Brian Underdown without him, this template would never exist, I would aslo like to acknowledge the following people: -

Jerry Dietrich for his massive contribution in converting my wild ideas into reality, putting me straight on my mediocre coding skills and having the patience of a dozen saints. Aslo Stephen, Sean, Chris, Ray, Mauro, Frank for their invaluable contribution.

Gary Roderick for his original coding of Highcharts for WeeWX.

William Bailey aka Lightmaster who maitains the MB version of Weather34. Incredibly helpful and always on the end of Telegram when I need a chat, night or day.

Ken True for sharing files and who makes my job of maintaining the WeeWX version so much easier.

Thomas Sosio for his invaluable contribution in producing the Meteobridge lookup code to translate WeeWX database output.

David Marshall for contributing technical knowledge and solutions to create some original .tmpl files and alternative solutions for weather alerts.

Taylormia for contributing his excellent setup example for instances where WeeWX and server/template are remote to each other.

Gary Portellas for a helpful suggestion to further simplify the installation process.

Drealine for his recent work on extending the French translations.

All those unamed people who have helped me with testing updates.

The creators of WeeWX without which there would be no point.

# Alternative versions

# Meteobridge
you can find the Meteobridge version maintained by Lightmaster (William) at 
https://github.com/weather34/Meteobridge-Weather34-Template34/

# Cumulus
you can find the Cumulus version maintained by Ken True (Saratoga) at 
https://github.com/ktrue/CU-HWS

# Weewx
you can find a Weewx version maintained by Ian Millard is also avaialble via 
https://github.com/steepleian/weewx-Weather34

# Weatherflow
you can find a Weatherflow version not maintained but fully tested as of May 5th 2019 
https://github.com/weather34/Weather34-Weatherflow


# This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License.
http://creativecommons.org/licenses/by-nc-nd/4.0/

# Credits and thanks to the contributors who made the original version of Weather34 possible between 2015 and 2019.

 Erik M Madsen for language idea and initial script
 
 Paul @komoka weather in Canada for continous support and testing 
 
 Josep for Spanish/Catalan language translation and for many ideas and refinements
 
 Pascal Catte French translation and ideas fowarded 
 
 Steve the developer of Cumulus for support and providing a platform to resolve issues 
 
 Mats Ahlklo Swedish translation and his work on using Davis weatherlink 
 
 Betejuice (Cumulus Forum) for providing a solution for meteor shower listings 
 
 Ken True (Saratoga) for kindly granting permission allowing use of many scripts he developed which gave inspiration and ideas  though not used today it was the inspiration that allowed to do something more suited to the design. 
 
 Eric Rechlin Special thanks for originally creating the theme switching and extensive work on metrics/non metrics
 
 Boris at smartbedded (meteobridge) for ongoing support and upkeep of meteobridge 
 
 Wim van der Kuil for the original meteobridge script 
 
 David St John at weatherflow for providing hardware for testing and his non bias logical views 
 
 Paul Wilman , Tina Thomas, Vaggos , Chuck M , Aaron Gersztoff , Ian Millard, and many many more for continous constructive supportive feedback .. 
