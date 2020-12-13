## IDS Project A5 Big Baby.
### Introduction
The goal of our project is to find factors, which predict fetal macrosomia. In other words, our aim is to find which attributes are linked to newborns, that are larger than 95% of all babies with the same gestation period. Our code can be found in this repository in the file named Project A5 Big Baby.ipynb.
The objective of this ReadMe is to give explanations to questions that may arise from code. Project uses following modules: pandas, sklearn, numpy, xgboos. For training the models the data file Pregnancy_data.csv is also required. 
### Cleaning data
Since the data file given to us was initally excel file, then it contained a lot of excesssive data. In this step, we got rid of duplicate data.
![PicA](readme_images/dropping.png)

### Data preprocessing
Firstly, we translated all remaining attributes to English.</br>
![PicB](readme_images/dropping.png) </br>
Visualising the data. </br>
![PicC](readme_images/visualising.png) </br>
Since some women were not weighed on their visits, then we interpolated their weights from their previous and next visit. </br>
![PicD](readme_images/missing.png) </br>
![PicE](readme_images/interpolating.png) </br>
Made new attributes for training. The thinking behind it is to check whether absolute difference or relative difference of weight predicts the result more accurately.</br>
![PicF](readme_images/featrue_engingeering.png) 

### Training
Splitting the data into training set, testing set, validation set.
Firstly, we translated all remaining attributes to English.</br>
![PicB](readme_images/split.png) </b
![PicB](readme_images/features2.png) </b
Firstly, we translated all remaining attributes to English.</br>
![PicB](readme_images/undersample.png) </b
![PicB](readme_images/undersampling_sets.png) </b
vFirstly, we translated all remaining attributes to English.</br>
![PicB](readme_images/undersample_a.png) </b
Firstly, we translated all remaining attributes to English.</br>
![PicB](readme_images/undersaple_b.png) </b
![PicB](readme_images/best.png) </b
Firstly, we translated all remaining attributes to English.</br>
![PicB](readme_images/m3.png) </b



