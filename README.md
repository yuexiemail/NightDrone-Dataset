# NightDrone-Dataset
Currently, there is a lack of benchmark datasets specifically collected for nighttime DroneDet.
As stated in a recent survey[1] on drone vision, two drone-captured benchmark datasets VisDrone and DroneVehicle are widely used for DroneDet. 
Moreover, only a small portion of images in both of the drone-based datasets are nighttime images, 
and the majority of the images in these two datasets were collected in the daytime.
To fill the gap in available datasets for nighttime DroneDet, we have created the NightDrone dataset.
In this section, we first present the data collection and annotation process of this 
dataset, and then compare it with the existing DroneDet datasets. 

Our NightDrone Dataset includes $6,805$ images collected by drones.
This dataset includes $5,445$ training images and $1,360$ testing images. 
$254,222$ objects were manually annotated with BBoxes. 
Each image in NightDrone includes an average of $37.36$ objects, of which the maximum number is $673$.
Our NightDrone dataset can be downloaded from: https://drive.google.com/file/d/1pLJDO582rDx6I9CRhqcrgGbEb4dFvWH-/view?usp=drive_link.



[1] P. Zhu, L. Wen, D. Du, X. Bian, H. Fan, Q. Hu, and H. Ling, “Detection and tracking meet drones challenge,” IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 44, no. 11, pp. 7380–7399, 2021
