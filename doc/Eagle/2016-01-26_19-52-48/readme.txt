**********************************************************
*****************Schematic Instructions  *******************
**********************************************************

To import your new Schematic file into Eagle:

1. Unzip the downloaded folder files to local directory and Start Eagle.
2. Select "File"->"Open"->"Schematic..." from the menu at the top of
   the screen.
3. Browse to your newly exported file and select the ".sch" file extension.
4. You should now see your schamtic available in Eagle.

**********************************************************
*******************  PCB Instructions  *******************
**********************************************************

To import your new BOARD file into Eagle:

1. Unzip the downloaded folder files to local directory and Start Eagle.
2. Select "File"->"Open"->"Board..." from the menu at the top of
   the screen.
3. Browse to your newly exported file and select the ".brd" file extension.
4. Planes will need to be repoured to update the polygon fills
	1. Once your board is loaded, type "ratsnest" into the command
	   line and press the Enter key.
	2. The polygons should all be filled now.
5. You should now have an image of your board available in Eagle.

**********************************************************
*******************  LIB Instructions  *******************
**********************************************************

To import your new library into Eagle:

1. Start Eagle.
2. Select "File"->"New"->"Library" from the menu.
3. In the blank library window, select "File" -> "Execute Script"
   from the menu.
5. Browse to your newly exported Eagle Script file (".scr" file extension)
6. After opening the file, the script will populate the new library.
   Layer 93 should NOT exist.
7. Use "File"->"Save" (or "Save As..") to save the library to the desired
   location in Eagle native format.

For additional information, please visit this site:
http://www.accelerated-designs.com/help/Eagle_import.html

You may also find this video helpful:
http://youtu.be/5jGuWY-Yy3Q

**********************************************************
**********************************************************
**********************************************************