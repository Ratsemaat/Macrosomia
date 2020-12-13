## IDS Project A5 Big Baby.
### Introduction
The goal of our project is to find factors, which predict fetal macrosomia. In other words, our aim is to find which attributes are linked to newborns, that are larger than 95% of all babies with the same gestation period. Our code can be found in this repository in the file named Project A5 Big Baby.ipynb.
The objective of this ReadMe is to give explanations to questions that may arise from code. Project uses following modules: pandas, sklearn, numpy, xgboos. For training the models the data file Pregnancy_data.csv is also required. 
### Cleaning data
Since the data file given to us was initally excel file, then it contained a lot of excesssive data. In this step, we got rid of duplicate data
![PicA](readme_images/dropping.png)

### Data preprocessing
Firstly, we translated all remaining attributes to English.</br>
![PicB](readme_images/dropping.png)
Viusalising the data
![PicC](readme_images/visualize.png)
Found missing data and interpolated the data where possible.
![PicD](readme_images/mssing.png)
![PicE](readme_images/interpolating.png)
Made new attributes for training.
![PicF](readme_images/ featrue_engingeering.png)




