# STAS_object_detection_comp
This is a repo for the STAS object detection competition (2022/4). Below is the introduction to each script.

**train.py**: We train YOLOv5 pretrain model using our training set. 

**Locate_STAS.py**: We plot the ground true boxes on the training images. 

**Tr_statistics.py**: Some statistics about our training images. 

**color_deconvolution**: We aply color deconvolution on our training images. 

**Preprocessing_for_YOLOv5.py**: We re-structure the data structure of our training set to fit the requirement of YOLOv5. On the other hand, one block in this script aims to extract the feature vectors, which design manually, of training images for the label clustering. 

**STAS_region_extractor**: We extract the regions that only cover the ground true boxes for the following label clustering. 

**label_clustering**: We do the label clustering here. 

**label_clustering_autoencoder**: We tried another way for label clustering. Did not finish this though.

test


