# image-search-engine
Search engine based on images. You pass an image as input and it gives other images related to the input as output.

As the dataset was too large to upload even in the zip folder, I used my drive to upload it -- https://drive.google.com/file/d/13b1Vq7ZK5EQpRrpDRbmBSDPLaOtCWukz/view?usp=sharing Downolad the dataset from here.

Queries are nothing but the images from the dataset used to pass into the engine.

desc_color.py - it will learn every image from its pixel intensities and making histograms of pixel intensities at different pixel level. 

gen_index.py - used to generate unique index for each image and assign its histogram's values to it.

engine.py - it is the heart of the program. it is where the input images are read and similar output images are found.

perform_search.py - it is where user will give the CLI input with appropriate path to index file and image file to begin the search.

problem - i can't make all the output images display at once using matplotlib grid, images will be popped one by one. SORRY for this i'll try to clear all bugs in future.

