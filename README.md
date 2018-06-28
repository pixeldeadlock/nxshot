# nxshot
Automatically organize and timestamp your Nintendo Switch captures
![image](https://user-images.githubusercontent.com/17756301/33006063-0c36d2ce-cdb0-11e7-8875-1044eab6527a.png)

## Requirements

* ``pip install pycryptodome``

* ``pip install BeautifulSoup4``

* (Optional) Screenshot key as ``key.txt`` on the same folder as nxshot for automatic updating. Hash: ``24e0dc62a15c11d38b622162ea2b4383``

## Usage

``nxshot.py FILEPATH``

Positional arguments:

>FILEPATH:    "Nintendo/Album" folder from your SD card.

![image](https://user-images.githubusercontent.com/17756301/33006113-3f204800-cdb0-11e7-99f4-94790c01916d.png)

Organized and tagged files are copied to ``../Nintendo/Album/Organized`` in a folder with the game's name.

If some of your screenshots end up being copied to ``../Nintendo/Album/Organized/Unknown``, please open an issue with the game id from the screenshot filename so that I can update the gameid list.

## Current gameid list

To see what games are currently automatically recognized, take a look at the [gameids.json](gameids.json) file.

The list is automatically updated from [SwitchBrew](http://switchbrew.org/index.php?title=Title_list/Games)
          
## Help

If you have any questions, feel free to send me a tweet [**@Some1CP**](https://twitter.com/Some1CP).
