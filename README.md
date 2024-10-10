# Machine-Learning-Project

In this project, we leverage machine learning to predict the manner in which barbell lifts are performed based on accelerometer data collected from multiple body positions. Our goal is to create a model that can automatically identify the type of lift being performed, whether it is executed correctly, and if not, what type of error is being made. By applying ML to this type of data, we can provide athletes, coaches, and healthcare professionals with valuable insights into exercise performance, ultimately leading to improved training programmes, reduced injury risk, and enhanced overall physical health.

## Introduction 
In recent years, the use of wearable technology such as fitness trackers and smartwatches has transformed the way people monitor their physical activities. Devices like Jawbone Up, Nike FuelBand, and Fitbit have popularised the concept of the quantified self, where individuals collect data on their activities to better understand their habits, improve their health, and achieve their fitness goals. However, while these devices can provide an accurate measure of how much activity is done, they often fall short in evaluating how well an activity is performed.

This is where Machine Learning (ML) comes into play. Machine Learning has the potential to revolutionise how we interpret physical activity data by providing deeper insights that go beyond simple step counts or calorie measurements. With ML, it is possible to detect subtle patterns in movement, distinguish between different types of exercises, and even evaluate the quality of those movements. This opens up new possibilities in fields such as sports science, physical therapy, and fitness training, where understanding the form and technique of exercises can be just as critical as understanding the quantity.

The project not only showcases the power of machine learning in analysing complex human movements but also highlights its role in providing data-driven insights that can optimise human performance and well-being.

## Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit, it is now possible to collect a large amount of data about personal activity relatively inexpensively. These types of devices are part of the quantified self movement—a group of enthusiasts who take regular measurements about themselves to improve their health, to find patterns in their behaviour, or simply because they are tech geeks.

In this project, we explore how to quantify not just the amount of a particular activity performed, but also *how well* it is executed. The goal is to use data from accelerometers on the belt, forearm, arm, and dumbbell of 6 participants, who were asked to perform barbell lifts correctly and incorrectly in 5 different ways. For more information, refer to the [Weight Lifting Exercise Dataset](http://groupware.les.inf.puc-rio.br/har).

## Data

The datasets for this project are available here:

- **Training Data**: [pml-training.csv](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv)  
- **Test Data**: [pml-testing.csv](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv)

These datasets contain measurements from accelerometers on the belt, forearm, arm, and dumbbell of the participants, as well as metadata about each exercise. If you use this data for any purpose, please be sure to cite the original source [here](http://groupware.les.inf.puc-rio.br/har).

## Project Objective

The main objective is to predict the manner in which each exercise was performed. This is represented by the `classe` variable in the training set. You can use any of the other variables for this prediction task.

The project includes the following steps:

1. **Data Cleaning and Preparation**: 
   - Handle missing values and remove irrelevant columns.
   - Filter variables with low variance to reduce noise.

2. **Model Building**:
   - Train various machine learning models, including:
     - Support Vector Machine (SVM)
     - Random Forest
     - Decision Tree
     - Gradient Boosted Trees

3. **Model Evaluation**:
   - Use cross-validation and performance metrics like accuracy and confusion matrices to evaluate each model.
   - Select the best-performing model for prediction.

4. **Prediction**:
   - Apply the chosen model to predict the `classe` variable for the test dataset.

## Repository Content

- **Project.Rmd**: R Markdown file containing the complete analysis and code.
- **Project.html**: Compiled HTML file with the analysis results.
- **README.md**: Overview of the project and repository contents.

## Project Highlights

- Developed a robust Random Forest model with an accuracy of 99.51%.
- Utilised various machine learning models to explore different prediction approaches.
- Cleaned and prepared the dataset for optimal model performance.
- Effectively used visualisation techniques to understand data distributions and model performance.

## Final Thoughts

This project demonstrates the process of building, evaluating, and selecting machine learning models for a real-world dataset. It showcases the application of data science to analyse human activities and predict outcomes based on sensor data.

**Repository Link**: [Machine Learning Project Repository](https://github.com/juanpaat/Machine-Learning-Project)

[!NOTE]  
If you have any questions or would like to discuss the project further, please feel free to reach out!


> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

