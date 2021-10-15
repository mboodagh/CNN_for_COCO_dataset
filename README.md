# CNN_for_COCO_dataset
This repository contains files for downloading the COCO images for ten categories and then performing classification for the images.  First, the "COCO_image_downloader.ipynb" file is used for downloading the images for the categoreis of interest for both training and validation. The downloaded images are stored in two separate folders for training and validation purposes. 
The file "hw04_training.ipynb" uses three different convolutional network structures (net1, net2 and net3) for the classification purpose. net1 uses one convolutional layer with one layer of pooling, whereas net2 contains two convolutional layers with two layers of pooling. Further, to investigate the effect of the presence of the padding, we construct net2 with padding and name it net3. The loss values are plotted for the three network structures and the network parameters are saved for validation.

The file "hw04_testing.ipynb" utilizes the networks trained in the file "hw04_training.ipynb" to compare the predictions of the networks for the test datasets. To this end, the heatmap is plotted. The net3 demonstrates better performance compared to net1 and net2. 
 
