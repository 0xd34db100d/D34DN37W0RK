+++
title = 'Winfix - script for fixing Windows 10/11 bugs'
date = 2023-04-10T15:30:59+05:00
tags = ['Windows 10/11', 'Scripts']
+++
[View on Github](https://github.com/0xd34db100d/winfix)

## Functions
Currently supported fixes:
  * Clipboard - fix Windows 10/11 clipboard (ctrl + c | ctrl + v not working)! Use "Winfix.exe clipboard" in cmd or click on button.
  * Internet - clear Windows 10/11 DNS Cache, renew IP, reset Winsock (Internet problems)! Use "Winfix.exe internet" in cmd or click on button.
  * Explorer - restart explorer.exe (Desktop bugs)! Use "Winfix.exe explorer" in cmd or click on button.

In the future I plan to add even more fixes!
## Installing
There's 2 ways how to install and use this script:
<br>
1. Download from releases page and add it to environment variables.
2. Install all dependencies and run it using python 3. 
* dependencies:
  * readchar (`pip install readchar`)
  * psutil (`pip install psutil`)
  * customtkinter (`pip install customtkinter`)
## Screenshots
 ![Screenshot of fixes list.](https://i.imgur.com/3G5WfXe.png)
***made with <3***
