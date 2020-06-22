# Natural-Scenes-Classification

![alt text](https://github.com/mohit138/Natural-Scenes-Classification/blob/master/images/train_2.png?raw=true)

This project classifies an image into various scenes(Buildings, Forest, Glacier, Mountain, Sea, Street). Tensor Flow API is used for solving the problem. 

Transfer Learning was applied with **InceptionV3** model. Pretrained weights were used for these layers. 
Some final layers of the pretrained model were not used, and a few layers were added at the end to help network train on custom dataset.


Following are some of the predictions made by the model : 

![alt text](https://github.com/mohit138/Natural-Scenes-Classification/blob/master/images/building_class.png?raw=true) 
Classified as BUILDINGS.

![alt text](https://github.com/mohit138/Natural-Scenes-Classification/blob/master/images/mountain_class.png?raw=true) 
Classified as MOUNTAINS.

![alt text](https://github.com/mohit138/Natural-Scenes-Classification/blob/master/images/street_class.png?raw=true) 
Classified as STREET.

![alt text](https://github.com/mohit138/Natural-Scenes-Classification/blob/master/images/forest_class.png?raw=true) 
Classified as FOREST.

![alt text](https://github.com/mohit138/Natural-Scenes-Classification/blob/master/images/sea_class.png?raw=true) 
Classified as SEA.

The model predicts preety accurately each scene it is presented with. Just after 2 epochs, it train accuracy was **83.3%** and validation accuracy was **89.77%**. 
