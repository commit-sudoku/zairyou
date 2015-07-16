![screenshot](https://raw.githubusercontent.com/commit-sudoku/zairyou/master/screenshot.png)

材料 - ZAIRYŌ
-----------

* This style is written only to work with ccd'0s 4chanX fork.

* This style currently only works on firefox.

* Big thanks to [mudanaku] [2] for updating and fixing this style.

* To get the board links to display properly, use the custom navigation found in the advanced section of the settings. Click [here] [3] for an example.

* Toggle the sidebar by toggling header auto-hide (Default keybind is shift + h).

* Click "掲示板" to open the full board list.

* Click "見てのスレッド" to open the thread watcher menu.

* Press 'Q' to open quick reply.

Installation
-------------------------------

* Install [ccd0's 4chanX] [1] userscript. 
* Install the [Stylish] [6] extension. 
* Navigate to the userstyles section of the [Addons] [4] page. 
* Click on "Write New Style", give it a name, and paste the CSS there. 
* Go into your 4chan X settings.
* Turn OFF 'Persistent QR', 'Thread Hiding Buttons', and 'Reply Hiding Buttons'
* I'm not sure if there are any other settings needed for it to look right, so my settings are [here] [5].
* Not necessary but [Source Han Sans] [7] is a great Japanese font, but if you don't have it installed this style will fall back to Meiryou

Customization
-------------------------------

CTRL + F 'http://i.imgur.com/2Uw0eQQ.png' and replace it with a path to your own 1920x64 header image or use the ones I left commented.

CTRL + F '#3F51B5' and replace it with a hexdecimal color of your choice to change the accent color. 

TODO LIST
-------------------------------
* fix post highlight going too far right 
* find way to add in file info
* use flex boxes to reorder posts elements
* maybe add icons
* maybe make drawer hover over posts
* add bigger backlink icons

[1]: https://github.com/ccd0/4chan-x
[2]: https://github.com/mudanaku/
[3]: https://raw.githubusercontent.com/commit-sudoku/zairyou/gh-pages/boardshelp.png
[4]: about:addons
[5]: http://i.imgur.com/x970AkQ.png
[6]: https://addons.mozilla.org/en-us/firefox/addon/stylish/
[7]: https://github.com/adobe-fonts/source-han-sans/tree/release
