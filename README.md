# Dataset-5-class
5 classes (door, sign, stairs, person and tvmonitor) dataset which is relevant to the indoor search-and-rescue scenario.
In total 805 annotated images used for training model and testing the performance of trained model.
80 additional plain images without any annotation, which can be used for testing the applicaiton in new environment.

### JPEGImages
805 JPEG images.

### Annotations
805 annotation files corresponding to the 805 JPEG images.

### SegmentationObjectPNG
805 segmentation png files corresponding to the 805 JPEG images.

### ImageSets/Main
train.txt the 644 training items
test.txt the 161 testing items
traintest.txt the combination of training and testing items

The ratio set for spliting the training and testing set is 4:1 in this work.

### AdditionalTestingImages

80 JPEG images without any annotation used for additional testing.

### class_name.txt
the name of 5 classes in this dataset.
