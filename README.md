# segmentationAlgorithm
Intro: Segments an image of a leaf but could be expanded to others based on thesholding choices.

Format: Utilizes jupyter notebook and so I left it in a PDF format to provide easy access to the code and the results.

Description: So to start we have our basic algorithm, and with the image being R/G/B we can threshold the matrix image to seperate the colors. We find the level of green we want and then do some post processing on the image such as removing small holes and objects to clean up the segmentation and then test to see what we get. After this we have the MSD/HD/DSC functions which in short are used to test the quality of the segmentation. We then iterate over all our images to see how well the algorithm performs on different ones. The last part is a comparison of our segmentation on the left, with the ground truth images, the true segmented images we use to test against on the right. We checked both our best result, and our worst result as the comparison.


Libraries Used: MatPlotLib, Numpy, Sci-Kit Learn.
