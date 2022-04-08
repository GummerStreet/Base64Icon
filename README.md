# Base64Icon 1.0.0
encode a PNG icon to base64 bytes for use as a Python program favicon

The program will encode a PNG image file containing an icon to base64 bytes, for use as a
favicon inside a Python program.
The favicon is the little icon that appears at the top left corner of the program window, in
the titlebar.
Click on the "Open" command in the "Edit" menu to load the PNG image. The program
will generate the base64 code.

To copy the result:

- Click on the "Copy" command in the "Edit" menu

		or

1. Select the text in the window
2. CTRL-C or right click-Copy

The package includes a demo Python script (demo.py), with the code needed to generate
an app window with a favicon. You can replace the bytes after the "img=" command with the
base64 bytes generated by processing your own icon with the program.
You can tweak to your needs the rest of the code to create a new program or merge it into 
an existing program.
