
# Project Description
This project is completed in Python. Nibabel, numpy, skimage, and CV2 packages are used in the project. In this project, the cerebral cortex is segmented by identifying the gray level of the image and contour. After obtaining the segment of the cerebral cortex: Method 1 determines the thickness by determining whether there are zero pixels around non-zero pixels. Method 2 uses cv2.distanceTransform to show the thickness.


The looking_down script and the looking_front script Is a segment and thickness map of a single slice of 2 views (default way). The looking_down_144 script and the looking_front_176 are used to correct the default contour function to get a correct thickness map. The all map_front script and the all map_down script will traverse all slices through two views.
