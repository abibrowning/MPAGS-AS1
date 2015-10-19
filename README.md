# MPAGS-AS1 - % Coverage Code
Code to analyse an image and determine the coverage of a sample both as a % and in square metres.
Modules needed: matplotlib.pyplot, numpy, mahotas

Basic steps:
- Import image (either from jpeg or from ibw)
- Create a threshold value from the image
- Use threshold value to simplify image
- Calculate area of high points
- Calculate total area of image (may need user input depending on file type able to read)
- Output image overlaid with the edges found using the threshold
- Output the % coverage and area coverage
