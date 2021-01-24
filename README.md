# Yellow Sticky Traps Dataset
This dataset contains images of yellow sticky traps and bounding box annotations for three classes of flying insects found in greenhouses.
The annotated classes are Macrolophus pygmaeus, Nesidiocoris tenuis and Trialeurodes vaporariorum (Whitefly).

The dataset is based on the original version **"Raw data from Yellow Sticky Traps with insects for training of deep learning Convolutional Neural Network for object detection"** by **A.T. Nieuwenhuizen et. al.** (see [source](https://data.4tu.nl/articles/dataset/Raw_data_from_Yellow_Sticky_Traps_with_insects_for_training_of_deep_learning_Convolutional_Neural_Network_for_object_detection/12707066)).
This version contains corrected annotations and uniform image orientations.

## Details
The yellow sticky dataset consists of:
* 284 **landscape JPEG images** of **5184 x 3456 px**
* 8114 **bounding box** annotations:
    * 1619 **Macrolophus pygmaeus**
    * 688 **Nesidiocoris tenuis**
    * 5807 **Trialeurodes vaporariorum (Whitefly)**

Compared to the original dataset by **A.T. Nieuwenhuizen et. al.** the Exif image rotation information were fixed to match the landscape-oriented images.

Additionally, the annotation quality was improved by labeling previously unlabeled objects, fixing wrong labeled classes, resizing bounding boxes and improving the location of bounding boxes.

The annotations were improved with [LabelImg](https://github.com/tzutalin/labelImg), created by Tzutalin. Ground truth information is stored in XML files in PASCAL VOC format.

The labeling process was carried out to the best of our knowledge.

# Credits
This dataset was created with the help of Carolin Vey.

## Source of original dataset
```
"Raw data from Yellow Sticky Traps with insects for training of deep learning Convolutional Neural Network for object detection"

A.T. (Ard) Nieuwenhuizen and J. (Jochen) Hemming and D. (Dirk) Janssen and H.K. (Hyun) Suh and L. (Lien) Bosmans and V. (Vincent) Sluydts and N. (Nathalie) Brenard and E. (Estefanía) Rodríguez and M.D.M. (Maria del Mar) Tellez

published: March 2019

DOI: 10.4121/uuid:8b8ba63a-1010-4de7-a7fb-6f9e3baf128e

https://data.4tu.nl/articles/dataset/Raw_data_from_Yellow_Sticky_Traps_with_insects_for_training_of_deep_learning_Convolutional_Neural_Network_for_object_detection/12707066
```
