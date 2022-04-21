# Predicting Childrens' Food Allergies

## Can we predict a child's future food allergies based on their current ones?

![image](https://user-images.githubusercontent.com/53787104/164481141-ea428cd1-d350-4e63-983f-addaf19b694b.png)

### Business Problem

The prevalence of food allergies in children has increased at a rapid rate within the past couple of decades. "Between 1997 and 2011, food allergies among children increased 50% and now affect 6 million US children" [1]:[source](https://community.kidswithfoodallergies.org/blog/10-shareable-images-for-food-allergy-awareness-week-1). 
As a millenial born in 1991, my elementary school experience was void of strict protocols on outside food, unlike the current school landscape. Classmates often had cupcakes or pizza brought in to celebrate birthdays and peanut butter crackers were the unofficial snack of field trips.

The stakeholder is Food Allergy Research & Education (FARE). The objective is to use existing data to predict and model patients' future food allergies. The ability to predict an increase of a specific food allergy identifies new trends and allows research to pivot and address them.

### Data

The dataset was obtained from [zenodo.org](https://zenodo.org/record/44529#.YmAFlZPMIiz). It entails information on food allergies alongside preexisting conditions on a peer reviewd study from the Children's Hospital of Philadelphia of patients born in 1983-2012. 
There were 333,200 individuals in the dataset. The columns were then pared down as listed below.

### Modeling and Evaluation

Modeling began with the dataset split, scaled, transformed and smote'd.
A Dummy Baseline was the first model and it resulted in a Train Accuracy of 50% and Test Accuracy of 6.8%. After One Hot Encoding I ran a Logistic Regression which resulted in a Train Accuracy of 75.45% and Test Accuracy of 89.33%. I followed up with a Decision Tree Classifier where milk, egg and peanut allergies occur at the highest frequency.

This model can be applied to 

In the future I would like to run an additional target also utilizing pre-existing traits of asthma and eczema as well in addition to having an adult dataset. Finally I would like to implement a risk level range estimation prediction.



## Repo Tree
```
├── Data                                 <- data folder
├── .DS_Store                            <- DS_store
├── .gitignore                           <- gitignore
├── Final_Allergy_Prediction_Notebook    <- Main Notebook
├── README.md                            <- readme overview
└──                                      <- Presentation PDF
```
