**Dataset:** http://www.josiahwang.com/dataset/leedsbutterfly/leedsbutterfly_dataset_v1.0.zip

LEEDS BUTTERFLY DATASET (v1.0)
==============================
http://www.josiahwang.com/dataset/leedsbutterfly/

Josiah Wang, Katja Markert, and Mark Everingham

For any enquiries please email Josiah at: jw (-åt-) josiahwang.com


Version history
===============
v1.0    29/11/2010    Initial release


Citation
========
If you use this dataset please cite the following work:

Josiah Wang, Katja Markert, and Mark Everingham.
"Learning Models for Object Recognition from Natural Language Descriptions".
In Proceedings of the 20th British Machine Vision Conference (BMVC2009), Sept 2009

@InProceedings{Wang09,
   title = "Learning Models for Object Recognition from Natural Language Descriptions",
   author = "Josiah Wang and Katja Markert and Mark Everingham",
   booktitle = "Proceedings of the British Machine Vision Conference",
   year = "2009"
}



Information
===========

This ZIP archive contains:
1. 832 images for ten butterfly categories (55-100 images per category), collected from Google Images and manually filtered.

2. Segmentation masks for each image

3. Textual descriptions for each butterfly category, obtained from http://www.enature.com/fieldguides/.


Images
======
The 'images' folder contains a total of 832 images for ten butterfly categories, in PNG format.
Naming convention: Each image is prefixed with the category ID of the butterfly (001, 002, ..., 010) followed by the sequence number of the image within the category. Please note that the sequence numbers may not necessarily be consecutive.

The scientific (Latin) names of the butterfly categories are:

001: Danaus plexippus	

002: Heliconius charitonius	

003: Heliconius erato	

004: Junonia coenia	

005: Lycaena phlaeas

006: Nymphalis antiopa	

007: Papilio cresphontes	

008: Pieris rapae	

009: Vanessa atalanta	

010: Vanessa cardui



Segmentation masks
==================
The 'segmentations' folder contains segmentation masks of each image in PNG format. Pixels with values 1 and 3 represent foreground pixels, and others background pixels.
Please refer to our BMVC2009 paper for more details on how the segmentation masks were generated.


Textual Descriptions
====================
The 'descriptions' folder contains 10 text files, each containing the textual description for a butterfly category. 
The files are named according to the category ID of the butterfly (001, 002, ... , 010) -- see the "Images" section above.

Each text file contains three lines:
Line 1: Scientific (Latin) name of the butterfly
Line 2: Common (English) name of the butterfly
Line 3: Textual description of the butterfly from eNature.com



Dataset webpage: http://www.josiahwang.com/dataset/leedsbutterfly/
Email: jw (-åt-) josiahwang.com

