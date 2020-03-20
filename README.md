# Flagella_tracking
Code to recognize flagella on pictures and extract info from them.
Include :
- image optimization: filtering, binarization
- testing line detection: select one image from a set, apply a Hough transform
(determined by minimum threshold for including a point, minimal line length, maximal number of gaps to consider a line a line).
- applying the transform and finding centroids, coordinates, center of mass
- apply the same parameters to a set of images
- plot trajectories of tracked flagella
