# GID-MTL
GID-MTL5 and GID-MTL15 datasets 
These datasets are used for multi-task learning of simultanelously conduct scene classificton and pixel-level land-cover classification. Every image in each dataset contains pixel-level land-cover labels and image-level scene label. 


The image is cropped from GID datasets [1] and set to a size of 224×224 pixels. The categories of the scene are the same as the categories of pixel-level annotations, except that pixel-level annotations further contain an undefined category. 


GID-MTL5 contains five land-cover categories. GID-MTL15 contains fifteen land-cover categories. The contained categories, the number of images per category, and some sample images of GID-MTL5 are shown in Fig.1. The same information for GID-MTL15 is shown in Fig. 2.

 *****
 
 ![fig1]( https://github.com/cheer00/GID-MTL/blob/master/fig1.png)
 Fig.1 Sample images of GID-MTL5. Each group displays an image corresponding to a scene category, and the corresponding segmentation map. The annotations below list the category, the number of scene images contained in the category, and the color of the pixel-level label.
 
 
***** 
 
![fig2]( https://github.com/cheer00/GID-MTL/blob/master/fig2.png)
 Fig.2 Sample images of GID-MTL15. 
 
 
 
*****


[1]	Tong X, Xia G, Lu Q, Shen H, Li S, You S, Zhang L (2020) Land-cover classification with high-resolution remote sensing images using transferable deep models. Remote Sensing of Environment 237:111322.
