# Humain-Lab-vine-trunk-dataset
Dataset with images of vine trunk

The HUMAIN-Lab Vine-Trunk database consists of images (.jpeg) of vineyard trunks along with the corresponding ground truth data (.txt) obtained using the Labellmg [1] online graphical image annotation tool. One of the objectives of this database is to motivate computer vision and machine learning researchers to develop practical solutions for deployment in smart vineyards. The database consists of images of vine-trunks and contains different datasets for training (2516 images, 629 original and 1887 augmented),evaluation (180 images) and testing (90 images). Three data augmentation techniques are used to  enlarge the training set: rotation (between -22 and +22 degrees), brightness (between -55% and +55%) and blur (up to 3.5 pixels). All images have a resolution of 416×416.

All images of the in-house designed  dataset are captured by an RGB high resolution Samsung NX500 Mirrorless camera from three vineyards of well-known North Greek wine producers as part of a national research program [2]. The images are collected under natural daylight including disturbances such as varying illumination or shadowing. These conditions are giving the adequate variety to the training process. The main challenge is that the trunks have the same brown colour with the background, i.e. the terrain, and that in all images more than one trunk is depicted causing great occlusions that obstruct the detection task.

Cite As:
E. Badeka, T. Kalampokas, E. Vrochidou, K. Tziridis, G. A. Papakostas, T. Pachidis, V. G. Kaburlasos, Real-time Vineyard Trunk Detection for a Grapes Harvesting Robot via Deep Learning, The 13th International Conference on Machine Vision (ICMV 2020), November 02-06, 2020, Rome, Italy

The Figures depict some representative images of the final dataset, to point out the diversity and difficulties. Occlusion due to vegetation or leaves on the trunk, blur effects due to the movement of the camera, illumination and shadowing conditions, are some of the common difficulties of the in-field trunk-detection task.
![alt text](https://user-images.githubusercontent.com/26176656/93201908-85ac4b80-f75a-11ea-973a-878c1b86cca1.jpg?raw=true)

References
[1] Tzutalin., “Labellmg,” Git code, 2015, <https://github.com/tzutalin/labelImg> (26 May 2020 )    
[2] “Personalized Optimal Grape Harvest by Autonomous Robot (POGHAR).”, Hum. Lab, 2018, <http://evtar.eu/> 
