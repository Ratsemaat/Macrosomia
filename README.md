## IDS Project A5 Big Baby.
### Introduction
The goal of our project is to find factors, which predict fetal macrosomia. In other words, our aim is to find which attributes are linked to newborns, that are larger than 95% of all babies with the same gestation period. Our code can be found in this repository in the file named Project A5 Big Baby.ipynb.
The objective of this ReadMe is to give explanations to questions that may arise from code. Project uses following modules: pandas, sklearn, numpy, xgboos. For training the models the data file Pregnancy_data.csv is also required. 
### Cleaning data
Since the data file given to us was initally excel file, then it contained a lot of excesssive data. In this step, we got rid of duplicate data
![PicA](readme_images/dropping.png)

### Data preprocessing
Firstly, we translated all remaining attributes to English.</br>
![PicB](readme_images/dropping.png) </br>
Visualising the data. </br>
![PicC](readme_images/visualising.png) </br>
Found missing data and interpolated the data where possible. </br>
![PicD](readme_images/missing.png) </br>
![PicE](readme_images/interpolating.png) </br>
Made new attributes for training.</br>
![PicF](readme_images/featrue_engingeering.png) 
### Training



