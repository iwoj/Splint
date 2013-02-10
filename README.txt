This project aims to make open source tools easier to use for creative professionals familiar with Adobe's Creative Suite and other canonical commercial systems.

Photoshop -> Gimp
-----------------

Adobe Photoshop has been the top software for image manipulation for the last twenty years. If you're looking for an open source alternative, Gimp is definitely the way to go.

  http://gimp.org/

Unfortunately, Gimp is pretty hard to use if you're used to Photoshop. One small change that can improve Gimp and make the transition easier is to modify it with PS-style key bindings.

Installation:

On Mac OS X just double-click the "Install (Mac)" file.

On all other platforms, copy src/<platform>/gimp/menurc to your gimp preferences directory. For example, on Linux:

  cp src/Linux/gimp/menurc ~/.gimp-2.6


Illustrator -> Inkscape
-----------------------

  http://inkscape.org/

Inkscape contains optional keybindings based on Adobe Illustrator. Simply copy them to your local Inkscape preferences.

On Ubuntu 12.10:

  cp /usr/share/inkscape/keys/adobe-illustrator-cs2.xml ~/.config/inkscape/keys/default.xml

---

A splint can fix a gimped leg.

