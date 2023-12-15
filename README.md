# Ossw_Final   
### Configuration   
##### 1. Import Libraries
* Import python libraries for machine learning, image processing, and calculation.   
##### 2. Load Traning Data and Test Data
* Load image files and save them as array in `data` and `test` variables which have label keys.   
##### 3. Delete Background
* Find the edges of the brain for all directions.
* And crop them so that We can get only brain image without background.   
##### 4. Data Augmentation
* Tilt train data for random small angle and add it to data.
* Move train data for random small pixels and add it to data.   
##### 5. Average Pooling, Histogram Equalization, and PCA
* Do average pooling to every data.
* Do histogram equalization to every data.
* Reduce dimension with using PCA.   
##### 6. Model
* soft voting RandomForestClassifier and ExtraTreeClassifier.
* print accuracy of the model for the test data.
### Operating Instruction
1. put test data on the path "tumor_dataset/Training"
#### Copyright 2023. Hong Sahoon   
### Contact Info   
* E-mail: sahunhong1@gmail.com
* phone: 01099373329
