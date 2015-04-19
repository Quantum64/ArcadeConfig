# Arcade

**Welcome to your very own Arcade repository!**

The Arcade repository helps you keep all your servers in sync by managing both worlds and configurations for every game and hub server, as well as control what IP(s) Arcade can be run on.  This repository, readme file, and all other files in it upon creation were generated by the automatic Arcade Setup tool. 

Directories
---

**Config**
 
The server configurations are stored in the [config](/tree/gh-pages/config) folder.  Each configuration goes in its gamecode’s folder.

Thses can be modified manually, but it is recommended to modify them with the tool located here: ([Windows]( http://quantum64.github.io/Arcade/util/ArcadeConfig.exe), [Other]( http://quantum64.github.io/Arcade/util/ArcadeConfig.jar))

**Worlds**

All worlds for a game are stored in a single package.  This package comprises of a “worlds.pkg” file, and a “worlds.hsh” file.  These files can *only* be created using the Worlds Packager tool, which can be downloaded here: ([Windows](http://quantum64.github.io/Arcade/util/WorldsPackager.exe), [Other]( http://quantum64.github.io/Arcade/util/WorldsPackager.jar))

Other Files
---

**IP.txt**

Contains either the literal IP of your server, or a cipher of your IP if you do not want it to generally be known.  This must be valid for Arcade to work.  This can be changed at any time by editing the file here on GitHub, or using the IP Update tool, which can generate the cipher instead of using your real IP.  This too can be downloaded here: ([Windows](http://quantum64.github.io/Arcade/util/IPUpdate.exe), [Other]( http://quantum64.github.io/Arcade/util/IPUpdate.jar))

**config/sql.yml**

Stores information on how to connect to your SQL server.  This option is only available if you are using a private GitHub repo (which is recommended).  The only reason you would want to use this is if your SQL information has changed, and you don’t want to edit the configurations of all of your servers. 

*Folder links are currently broken due to the way GitHub handles relative links*
