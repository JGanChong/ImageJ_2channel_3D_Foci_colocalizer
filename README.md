# ImageJ_2channel_3D_Foci_colocalizer
Uses a distance radius to colocalize foci in 2 channels in the 3D space.

Macro applies a set of filters to both channels with user adjustable values before using a custom thresholding method with user adjustable variable to segment image.
ImageJ 3D suite is then used to calculate the distances between particles and define all particles within user set radius.
A result table with number of particles in both channels as well as foci within the radius is displayed.

Macro applies bleach correction to red channel (channel 1) only. radius is in the unit set by the image, if no units then it uses pixels.
