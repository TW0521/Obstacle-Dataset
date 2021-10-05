# Obstacle-dataset OD
Dataset for fifteen types of obstacle detection, Because the data is too large to put in Github, please click the link to get it from [Googledriver](https://drive.google.com/drive/folders/1ksPQTc1BkBljqLqEtIWmXFnkgHWs9Hqv?usp=sharing).[Baidu CODE:0521](https://pan.baidu.com/s/1NquX0rmVngvTAV82A-NkMg)

Classes ["stop_sign","person","bicycle","bus","truck","car","motorbike","reflective_cone","ashcan","warning_column","spherical_roadblock","pole","dog","tricycle","fire_hydrant"] Need to underline the category name

This obstacle dataset follows the format of the VOC dataset, if you are not clear about the VOC data format, please [click THERE to view](http://host.robots.ox.ac.uk/pascal/VOC/).

The dataset contains xml files in VOC format and .txt files for yolo training,as follows.<br>

VOC format.<br>
-
-JPEGImages<br>
-Annotations<br>
-ImageSets<br>
　--Main<br>
　　---train.txt<br>
　　---test.txt<br>
　　---val.txt<br>
According to pictures and labels,as follows.<br>
　　img-train for training Contains 5066 images　　ann-train<br>
　　img-test for test Contains 1583 images　　　　　ann-test<br>
　　img-val for validation Contains 1266 images　　　ann-val<br>


yolo format．<br>
-
	lables　　　　#all picture labels<br>
	label-train　　#labels for training<br>
	label-test　　　#labels for testing<br>
	label-val　　　　#labels for validation<br>
This dataset contains images from the VOC dataset, the COCO dataset, and the TT100K dataset,It also contains some pictures collected by the author's team in the field.<br>

[VOC](doi:10.1109/CVPR.2014.13)<br>
-
Vicente S, Carreira J, Agapito L, Batista J. Reconstructing PASCAL VOC. Proc IEEE Comput Soc Conf Comput Vis Pattern Recognit. 2014:41-48. <br>

[COCO](doi:10.1007/978-3-319-10602-1_48)<br>
-
Lin TY, Maire M, Belongie S, et al. Microsoft COCO: Common objects in context. Lect Notes Comput Sci (including Subser Lect Notes Artif Intell Lect Notes Bioinformatics). 2014;8693 LNCS(PART 5):740-755. <br>

[TT100K](doi:10.1109/CVPR.2016.232)<br>
-
Zhu Z, Liang D, Zhang S, Huang X, Li B, Hu S. Traffic-Sign Detection and Classification in the Wild. Proc IEEE Comput Soc Conf Comput Vis Pattern Recognit. 2016;2016-December:2110-2118. <br>



if you have any question,You can contact me according to the following email.<br>
E-mail:`tangwu0521@gmail.com`<br>

The author continues to update this dataset.<br>
If you feel helpful to you, please light up the stars.
