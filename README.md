# microscopy_jupyter
working repository for electron microscopy jupyter notebooks


**4 files from Daniel Mejia:**

1. Original.ipynb: This is basically a copy-paste of the code on a Jupyter notebook, if you run it, this will show static images, but matplotlib interactivity does not work on jupyter.

2.  Interactive.ipynb: All matplotlib interaction was ported to Plotly / ipywidgets, the only difference is that the user will have to click instead of mouseover on the main image.

3.  Screenshot.png: This is just an image to show you how I'm rendering/comparing both notebooks

4.  09_2DWrinkAu_640kx_770mm_70um_0p64mrad_ss8_50x_50y_100z_216step_x256_y256.raw: this is a fake image that I created to run the code. The last cell (under comments) on Interactive.ipynb is the code I used to create this image (num_pixels is the resolution you want on the main image).