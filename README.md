# coco_to_voc_segmentation
Python code that takes an MS COCO JSON segmentation annotation file as input and generates corresponding VOC XML annotations.

This code will iterate over all the images in the MS COCO JSON segmentation annotation file, create corresponding VOC XML annotations, and save them to the specified output directory. 

Note that you will need to modify the coco_categories dictionary to include the names of the categories in your MS COCO JSON segmentation annotation file, and the voc_classes list to include the names of the classes you want to use in your VOC XML annotations. 
Also, you may need to modify the code to handle other aspects of your specific annotation format or use case.
