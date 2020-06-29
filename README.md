# Obstacle-dataset
Dataset for fifteen types of obstacle detection
You can download the completed dataset from here（）

Classes ["stop_sign","person","bicycle","bus","truck","car","motorbike","reflective_cone","ashcan","warning_column","spherical_roadblock","pole","dog","tricycle","fire_hydrant"]

This obstacle dataset follows the format of the VOC dataset, if you are not clear about the VOC data format, please click this link to view（http://host.robots.ox.ac.uk/pascal/VOC/）.

The dataset contains xml files in VOC format and .txt files for yolo training,as follows.

VOC format
-JPEGImages
-Annotations
-ImageSets
  --Main
    ---train.txt
    ---test.txt
    ---trainval.txt
    ---val.txt
    
According to pictures and labels,as follows.
img-train for training Contains 5066 images     ann-train
img-test for test Contains 1583 images          ann-test
img-val for validation Contains 1266 images     ann-val


yolo format
lables      #all picture labels
label-train #labels for training
label-test  #labels for testing
label-val   #labels for validation
This dataset contains images from the VOC dataset, the COCO dataset, and the TT100K dataset,It also contains some pictures collected by the author's team in the field.

[VOCdataset]
Vicente S, Carreira J, Agapito L, Batista J. Reconstructing PASCAL VOC. Proc IEEE Comput Soc Conf Comput Vis Pattern Recognit. 2014:41-48. doi:10.1109/CVPR.2014.13
[COCO]
Lin TY, Maire M, Belongie S, et al. Microsoft COCO: Common objects in context. Lect Notes Comput Sci (including Subser Lect Notes Artif Intell Lect Notes Bioinformatics). 2014;8693 LNCS(PART 5):740-755. doi:10.1007/978-3-319-10602-1_48
[TT100K]
Zhu Z, Liang D, Zhang S, Huang X, Li B, Hu S. Traffic-Sign Detection and Classification in the Wild. Proc IEEE Comput Soc Conf Comput Vis Pattern Recognit. 2016;2016-December:2110-2118. doi:10.1109/CVPR.2016.232



if you have any question,You can contact me according to the following email
E-mail:tangwu0521@gmail.com

The author continues to update this dataset
