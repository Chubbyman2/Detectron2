# Detectron2
Work done with Detectron2 for research. Details may be disclosed later.

Dataset used was a set of 20 images downloaded from Google of the main cast of the TV show Suits. Utilizing LabelMe, the heads of the characters were labelled. As can be seen, due to the limited amount of data and somewhat hasty labelling by me, Detectron2 had some trouble differentiating between some characters (i.e. Harvey and Mike, Rachel and Donna and Jessica). This was to be expected, and can be improved upon with more labelled data with classes having more distinct shapes.

Credits to Chengwei for his code and process on how to create a custom Coco dataset for Detectron2: 

https://www.dlology.com/blog/how-to-create-custom-coco-data-set-for-instance-segmentation/
