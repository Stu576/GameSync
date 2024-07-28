# GameSync


GameSync is a solution to a problem i face when playing retro games across multiple systems. It should be a lot easier to have these saves work across different platforms. The current iteration will support Windows and work as a centralised location for connecting to network storage and comparing file edit times. The future of this application will come in the form of a dedicated application that will run on the homebrewed system itself and connect to different storage locations.

The project is born from the fact that I play games across multiple systems. I may start a GameBoy Colour game on my Nintendo 3DS, but then decide i want to continue this on my iPad via Delta. After having to move file manually for a short while, i decided it is time to get this process automated.

The end goal is to have an application that runs on a 3DS, Switch etc that can connect to a common location such as Dropbox, iCloud and use those storage options as a basis for keeping the main versions of game saves. Pretty much like what Delta on iOS does.

Version 1. Initial 
1. Implement basic interface (Command-Line).
2. Build Local file strcture of storing data.
3. Connect to Network Location.
4. Initially it will only copy NDS saves based upon the 3DS loaders that launch those games. You can select where to store them.
