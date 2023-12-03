# NightDrone-Dataset
Currently, there is a lack of benchmark datasets specifically collected for nighttime DroneDet. As stated in a recent survey[1] on drone vision, two drone-captured benchmark datasets VisDrone and DroneVehicle are widely used for DroneDet. Moreover, only a small portion of images in both of the drone-based datasets are nighttime images, and the majority of the images in these two datasets were collected in the daytime. To fill the gap in available datasets for nighttime DroneDet, we have created the NightDrone dataset. In this section, we first present the data collection and annotation process of this dataset, and then compare it with the existing DroneDet datasets. 

Our NightDrone Dataset includes $6,805$ images collected by drones.
This dataset includes $5,445$ training images and $1,360$ testing images. 
$254,222$ objects were manually annotated with BBoxes. 
Each image in NightDrone includes an average of $37.36$ objects, of which the maximum number is $673$.
Our NightDrone dataset can be downloaded from: https://drive.google.com/file/d/1pLJDO582rDx6I9CRhqcrgGbEb4dFvWH-/view?usp=drive_link.

\textbf{VisDrone (Night): }
From VisDrone[1], we carefully selected the nighttime images and their corresponding annotation files to build our experimental dataset VisDrone (Night), which includes $1,008$ training images and $253$ testing images.
The spatial resolution of the images is approximately $2,000 \times 1,500$ pixels. 
These images are annotated with giving BBoxes into ten pre-defined categories, i.e.,
\textit{Truck, Bus, Car, Van, Awning-tricycle, Tricycle, Motor, Bicycle, Person, Pedestrian}, same as those in VisDrone.
The VisDrone (Night) Dataset is avaliable at: https://drive.google.com/file/d/1-od7QvvXSEI2Sl_K43bjCbX9mP1HpOQp/view?usp=sharing.

\textbf{DroneVehicle (Night):} 
As the first drone-based cross-modality dataset for vehicle detection, DroneVehicle contains pairs of RGB and infrared images. Similarly, we carefully selected image pairs collected during the nighttime and then chose only RGB images with annotated ground truth to build the DroneVehicle (Night) dataset. 
As a result, the new DroneVehicle (Night) includes $4,279$ training images and $438$ testing images,
where each image has a spatial resolution of $640 \times 512$ pixels. The images are annotated with defined BBoxes into five vehicle categories, i.e., \textit{Bus, Fright Car, Truck, Car and Van}, same as those in DroneVehicle.
The DroneVehicle (Night) Dataset can be downloaded from the URL: https://drive.google.com/file/d/1-stLRJ1JVMBgkeyfAZgvOa5J9vvUvwI5/view?usp=sharing.

[1] P. Zhu, L. Wen, D. Du, X. Bian, H. Fan, Q. Hu, and H. Ling, “Detection and tracking meet drones challenge,” IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 44, no. 11, pp. 7380–7399, 2021
