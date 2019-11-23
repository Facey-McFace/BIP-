# BIP-😸
BIP😸 is an informational BIP that outlines a general guideline for encoding Bitcoin addresses as strings of emoji. It includes example code for working with emoji addresses.


### OUTLINE OF WORK...

1. Grab all images from here:
https://unicode.org/emoji/charts/full-emoji-list.html

2. Parse the table using this:
https://unicode.org/emoji/charts/full-emoji-list.html

3. Save each image as a PNG with a name like:
cldr_short_name-platform.png

Note:
> 00:47 < Terminus> faceface: echo \
>   "R0lGODlhEAAMAKIFAF5LAP/zxAAAANyuAP/gaP///wAAAAAAACH5BAEAAAUALAAAAAAQAAwAAAMsWLPcrSHKOVcgOOtsiRCbBxLdF5rkcIVhx27uy6kagNlafOM5LXMKh3BRSAAAOw==" \
>   | base64 -d > ~/foo.gif
> 00:47 < Terminus> it's a gif btw so the mimetype is wrong.

4. Apply random transformations using Keras:
https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html

5. Try to classify cldr regardless of platform...

Note:
Find the list of cldr that are most accurately classified across platforms (e.g. those that are most similar / least confused across platforms).

Note:
Classification or OCR?

6. Create a list of 58 robustly classified emoji across platforms.

7. Map them to base 58 characters... Somehow.

8. Create libraries to work with this encoding.

