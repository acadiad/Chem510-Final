# Chem510-Final
Takes TIRF microscopy images of single molecules binding to a lipid bilayer and returns the probability of seeing a molecule of a certain brightness bound.

## Input Files
Takes z-stacks that have been sepearted into individual, 8-bit grayscale, jpegs. The first image inputed is the first image recorded on the microscope (i.e. the first z-stack). The rest of the images are read through in the for loop at the bottom half of the code

## Packages Required
* Pillow
* skimage
