# Java-console

Impleneation of terminal with some commands in Java. The purpose of this project was to get confident with Java UI, rather than create strong terminal commands.

## Index
   - [Demo](#Demo "Goto Demo")
   - [Features](#Features "Goto Features")
   - [Commands](#Commands "Goto Commands")
   - [Issues](#Issues "Goto Issues")



## Demo

![alt text](https://github.com/DZykov/Java-console/blob/main/img/show_case.png)

![alt text](https://github.com/DZykov/Java-console/blob/main/img/show_case2.png)

![alt text](https://github.com/DZykov/Java-console/blob/main/img/show_case3.png)

https://user-images.githubusercontent.com/38252337/188289701-c499e240-f216-41c4-a704-ec8cc14bbc79.mp4

## Features
- History of commands
- Up/down arrows to scroll comands from history
- Lazy encription/decryption
- Customizable style
- Loops for the commands
- Dynamic search for files and folders
- Youtube search 
- Website admin check
- Trace

## Commands
|Command | Description|
|--------|------------|
|-help                                                   | shows the list of all commants
|-clear/cls                                              | cleans the console’s display
|-popup [text]                                           | creates a window with a [text]
|-loop [int]                                             | repeats next command [int] times
|-start [path to folder/path to object/name of a program/path to website]| starts/opens file/folder/application/web page
|-trace true/false                                       | enable/disable trace
|-get [ip/time/date]                                     | shows ip/time/date
|-exit			                                         | closes console
|-search [directory] [name/format of file]               | searches for directory or file
|-show [path]                                            | shows all files, folders (even hidden)
|-create [file/folder] [path] [name,format/name]         | creates file or folder
|-read [path]	                                         | reads/outputes file context
|-process                                                | shows all processes
|-kill [process]                                         | kills a process (type name or id of a process)
|-play [maze/agario/snake/slither]                       | opens web game according to argument
|-crypt/encrypt [path to the file] save/delete [path to a new file] [name of file.format] delete*(optional; deletes new file) | crypted/encrypted text will be displayed
|-youtube/utube [key words]	                             | opens a video from youtube which matches key words in default browser
|-calc [int] [mathematical symbol] [int]                 | simple calculator command
|-calc [int] ! 1	                                     | calculates factorial
|-calc 1 [cos/sin/tan] [int]                             | calculates trigonometric function
|-adcheck http://example.com/                            | checks for admin page on the website
|-hide	                                                 | hides console
|-text color [r, g, b]/[color in words (red/white/etc)]	 | changes the color of a text
|-text font [size(integer)] [name of the font]		     | changes the font of a text
|-back [r, g, b]/[color in words (red/white/etc)]	     | changes the background color
|-size [integer for width, integer for height]/[normal]	 | changes the size of a console

## Issues
- This application was made for windows; however, it stills runs on ubuntu/mac but some commands don't work, and tray is not supported
