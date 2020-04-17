# Dermatology diseases classification

In this project, it was used principal component analysis (PCA), cross-validation and machine learning classification algorithms, to classified 6 different dermatological pathologies. 

#### Data
Each line corresponds to a patient and contains 34 attributes and their class (the last value of each sample). Some samples include invalid values represented by the '?'. The complete description of this dataset can be found at: https://archive.ics.uci.edu/ml/datasets/Dermatology

Class Distribution:
       Database:  Dermatology
       
       Class code:   Class:                  Number of instances:
       1             psoriasis			    112
       2             seboreic dermatitis             61
       3             lichen planus                   72
       4             pityriasis rosea                49
       5             cronic dermatitis               52    
       6             pityriasis rubra pilaris        20

<img src="./images/concrete.jpg" width=70% height=70% align="center"> 

The code contains:
* Data preparation: Class dataset
* Simple model with an input and output layer
* Resnet18 model

