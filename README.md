CSS-persent-code Language Percentage encoding of the selected text in the editor.
This encoding is used when including SVG images in CSS-background . 
The encoding result is placed in a pop-up message box.

KOMODO-CSS-PERSENT-CODER consists of three parts:
 1. Javascript code to convert a scalable vector graphics (SVG) image to a percentage code (CSS-present-code.ktf).
 2. Javascript code for the reverse operation - converting the percentage format code to SVG code (CSS-persent-encode.ktf).
 3. Javascript code to convert Jpeg and Png images to BASE64 format and insert this code into a CSS document (BASE64.ktf).

Each of the parts is for use in the ACTIVESTATE KOMODO EDIT and ACTIVESTATE KOMODO IDE.

How to use:

1. Inserting svg code into css file. Open the css file for editing. Open a small svg file in another window. 
Select the SVG code and press ALT + <. 
A pop-up window will display the percentage code. 
You can select and copy this code and paste it in the CSS background line.
                                         
2. The back operation. Open the CSS file with the percentage code. 
Select this code and press ALT + >. 
A pop-up window will show the SVG code for this snippet.
 
3. BASE64 encoder. Place the cursor on the line <img src = \"\"> between the quotes. 
Press ALT + /. The file manager will open. Select a small Jpeg or PNG image on your computer. 
The BASE64 code will be inserted in quotes.

You can see animated demo GIFs of any parts the KOMODO-CSS-PERSENT-CODER in the "/images" folder.
