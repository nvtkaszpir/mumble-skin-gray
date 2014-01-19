Mumble Gray skin
================

# About #

This is Mumble (http://mumble.info) skin created for those, that does
not like default white look of the application, because it can melt
your eyes in the middle of the night.

So I've decided to tweak my old skin, and ended up in creating a new
one, because 100% black is not always the best solution.

# Installation #
Easy, go to your Mumble configuration directory, there should be a
catalog named skins/, enter it. 

If you do not have git installed then just click Download Zip on the 
right of this page, and unpack that zip to the skins/ directory.

Then go to Mumble client, select Options > Configuration > Interface,
browse to the directory where you cloned the repo and select .qss
file that is in there. Make sure to select Plastique window style, and
then press OK.

Notice, sometimes you must restart mumble client to load all images from
the skin directory - especially when you are missing icons in channel list.

If you have a git installed then clone this repo in the skins/ directory,
for example
```
$ cd /home/kaszpir/Apps/Mumble/skins/
$ git clone https://github.com/nvtkaszpir/mumble-skin-gray.git
```

# ToDo #
1. Test skin on different platform, tested under Win7 and Ubuntu Gnome.

# Known issues and todo #
1. Channel/User comment shows with standard yellow color in the 
background, yet the text is gray.
2. URL links in Dialog boxes are blue.
3. Bottom area in wizard dialog box is white under Windows.

# License #

http://creativecommons.org/licenses/by-sa/4.0/
More detail in LICENSE.md

# Preview #

![Preview hosted on imgur](http://i.imgur.com/RRwJPjo.png)
