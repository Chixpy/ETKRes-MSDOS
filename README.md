# ETKRes-MSDOS
Resources for Emuteca: Microsoft MSDOS

Icons, images, texts, videos, etc. for use with [Emuteca](https://github.com/Chixpy/Emuteca).

## About Images

### Screenshot, Titles

Rule #1: No filters to screenshots.

All images in .png format at original resolution... if it is 4:3 (320x240; 640x480; 800x600; 1024x768; 512x384; etc.)

**TO DO**: Take a decision about resolutions wich are not 4:3 (320x200; 640x350; etc). In MSDOS era, screens were 4:3. So pixels were not squares; 5x6 rectangle make a square in 320x200/640x400/1280x800; 35x48 in 640x350 (11x8 and 37x27 are valid approximations). In the other hand some games seem to be aware of this; and in the worse case have mixed aspect relations it its elements.

### Front, Back, Spine, Ads, Reviews, Media, Other

Escaned .jpg; with a maximum of 2048x2048, don't enlarge artificially (if larger, we can resize it to 2048 the larger side, keeping aspect ratio and a quality of 90%). Trying not to do transformations and resave it. Lossless rotation or cropping allowed.

### Icons, Logos

Rule #1: Only 1 image for group or game. No folders with multiple images.

Icons are mainly extracted from game screenshots at original resolution. Usually they are protagonist frames, lives icons or recognizable icon.

Logos are usually extracted from Title or Main Menu screens.

All images are .png format. Width and Height are variable, using it's original size without resizing to a fixed size or adding more border to make it square. Emuteca handle they automatically.

The only time that the image will be scaled is when all 'icon pixels' are 2x2, 3x3, etc. pixels.

After extracting the icon image with transparent background, a border is added: Middle grey, half transparency (128, 128, 128, 128). 

[Emuteca](https://github.com/chixpy/emuteca) has [ETKIconBorder](https://github.com/Chixpy/Emuteca/blob/master/bin/Tools/ETKIconBorder.exe) tool in its distribution. A simple image editor to cut, extract, make transparency in images and apply filters to original image.

Altenatively, there is a GIMP's script too, that can add the border automatically after transparent background is created. But it's slooooow.

**TO DO**: As with images; think what to do about not 4:3 resolutions.

## Download

Use GIT to clone the repository or download it in zip:

https://github.com/Chixpy/ETKRes-MSDOS/archive/master.zip