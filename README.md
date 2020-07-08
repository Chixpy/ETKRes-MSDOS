# ETKRes-MSDOS
Resources for Emuteca: Microsoft MSDOS

Icons, images, texts, videos, etc. for use with [Emuteca](https://github.com/Chixpy/Emuteca).

## About Icons

Icons are mainly extracted from game screenshots at original resolution. Usually they are protagonist frames or lives icons (if they are similar to protagonist).

All images are png format. Width and Height are variable, using it's original size without resizing to a fixed size or adding more border to make it square. Emuteca handle they automatically.

The only time that the image will be scaled is when all 'icon pixels' are 2x2, 3x3, etc. pixels.

After extracting the icon image with transparent background, a border is added: Middle grey, half transparency (128, 128, 128, 128). Emuteca have a GIMP's script in its distribution, that can add the border automatically after transparent background is created.

**TO DO**: Take a decision about resolutions wich are not 4:3 (320x200; 640x350; etc); In MSDOS era, screens were 4:3. So pixels were not squares; 6x5 rectangle make a square in 320x200/640x400; 48x35 in 640x350 (11x8 and 37x27 are valid approximations). In the other hand some games seem to be aware of this; and in the worse case have mixed aspect relations it its elements.

## Download

Use GIT to clone the repository or download it in zip:

https://github.com/Chixpy/ETKRes-MSDOS/archive/master.zip
