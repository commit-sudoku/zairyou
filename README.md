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

Go to line 15 and replace #cb073c with another hexdecimal color to change the accent color. 

Go to line 112 and replace 'https://raw.githubusercontent.com/commit-sudoku/zairyou/master/res/bg/7.png' with a path to your own 1920x64 header image or use the ones I left commented.

[1]: https://github.com/ccd0/4chan-x
[2]: https://github.com/mudanaku/
[3]: https://raw.githubusercontent.com/commit-sudoku/zairyou/gh-pages/boardshelp.png
[4]: about:addons
[5]: http://i.imgur.com/x970AkQ.png
[6]: https://addons.mozilla.org/en-us/firefox/addon/stylish/
[7]: https://github.com/adobe-fonts/source-han-sans/tree/release

![dubs](https://raw.githubusercontent.com/commit-sudoku/zairyou/master/dubs.png)

This style also comes with the added feature of checking dubs. When someone's post number ends in repeating intergers, a checkmark will be added behind it to notify you of this. If this funcionality bothers you, it can be disabled by commenting out all lines from 1736 to 1786.
