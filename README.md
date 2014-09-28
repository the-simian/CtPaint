# CtPaint

CtPaint is basically a clone of MSPaint in browser.

Its not near completion, and I have no releases of it yet.

# Navigating this repo

ctpaint.coffee is the file run in the browser via ctpaint.html. gulpfile.js concatenates the many coffeescript files found in the various folders mainAct, postures, and initialization, into ctpaint.coffee

Initilization contains coffeescript files that mainly define functions and global variables. mainAct.coffee mostly handles user mouse and keyboard input. Postures contains tool-specific user input functions. The basic flow of the CtPaint is the mainAct registering an event, then refering to tool-specific functions (postures), which in turn give information to functions used by those tools.

Assets contain the images of the icons, toolbars, and glyphs

deletedScenes contains images of my notes during this project, as well as images of my MSPaint work environment while drawing the assets.

glyphGeneration contains a python file and some png files. The python file recolors the png files to make many of the assets I use.

spriteGeneration contains a python file and a png file. The python file crops sections out of the png file to make all the icons and toolbar images I use.

# Demos

This is a video of me talking about CtPaint's capacity to change colors in the palette: http://youtu.be/U08Llsl9dMk

Here is an image showing off the square tool:
http://i.imgur.com/5SgwLE9.png

Here is an image showing off the color options:
http://i.imgur.com/iRnMbcg.png

Here is an image showing off various tools:
http://i.imgur.com/UR9H3aE.png

# Feature list

Here is an incomplete list of features, with the ones I have finished checked off:

* X Circle tool
* X Circle fill
* X Circle with border
* X Color Palette with changeable colors
* X Copy
* X Paste
* X Cut
* X Fill tool
* X Flip canvas
* X Flip Selected region
* X Horizontal swap of Color Swatches 
* X Vertical swap of Color Swatches
* X Invert colors of canvas
* Invert colors of selected region
* X Line Draw tool
* X Undo
* X Redo
* Open File
* X Replace color
* X Resize canvas by click and drag
* X Resize canvas by text field
* Arrow key scrolling
* X Rotate Canvas
* Rotate selected area
* X Sample color
* Scale canvas
* Scale selected area
* X Select area
* X Square draw tool
* View mode
* Zoom
* Tool cursor images
* Secondary color transparency

General to dos and bugs to fix:

* Mouse canvas exit
* redo resize memory

------- LICENSING

ChadTech License (Ct)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software without restriction, including without limitation the rights to use, copy, modify, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is purnished to do so, subject to the following condition:

Involved projects, firms, and persons that utilitze this software be renamed 'Chadtech'