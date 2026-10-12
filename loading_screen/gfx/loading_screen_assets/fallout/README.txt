FALLOUT RECLAMATION - loading screen images
============================================

Put exactly these 3 files into this folder:

  loading_screen_1.dds
  loading_screen_2.dds
  loading_screen_3.dds

Format:
  - Size: 16:9, ideally 3840 x 2160 (vanilla uses 3838 x 2158)
  - DDS, compression BC1/DXT1 (no transparency) or BC3/DXT5, with mipmaps
    (e.g. GIMP or paint.net "Save as DDS", or Photoshop with the Intel/NVIDIA DDS plugin)
  - PNG is NOT supported here (the image is drawn as a 3D layer, not as a GUI icon)

The game picks one of the 3 at random on every loading screen.
Definitions:
  loading_screen/gfx/images/fallout_loading_screens.txt  (image file paths)
  loading_screen/gfx/scenes/00_loading_screens.txt       (the 3 static scenes)
