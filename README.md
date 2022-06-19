# price-scraper
This program runs through pricecharter.com to find the total of any set of games, comics, etc., put together.
 
Before you use this program, you will need to download Python, as well as a few packages.
To install Python, [click here](https://www.python.org/downloads/) and select your operating system.
The installer will download, and you must run it from the download location.

After you download python, open a terminal (CMD, Powershell, Terminal, etc.) and type the following commands:
pip install requests
pip install bs4
pip install datetime

After this, you should be able to run it!

To use the program you must know a few things: the console and the product ID of the game you are trying to add.
The product ID can be found by searching it on pricecharting.com and hovering over the title. The ID will be a series of numbers.

I plan on adding support for PAL and JAP territory games in the future, but NTSC is currently the only region supported.
Please suggest any features that you would like to see added and I hope this program is of use to you!
