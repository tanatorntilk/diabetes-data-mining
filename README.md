# The Diabetes Analysis
Researcher: Tanatorn Tilkanont
Analysed Since: 11 November 2023
University: Master of Science in Biomedical and Health Informatics, Faculty of Tropical Medicine, Mahidol University, Thailand

# 1. Introduction

Diabetes mellitus, a chronic metabolic disorder, is characterized by elevated blood glucose levels resulting from defects in insulin secretion, insulin action, or both. It poses a substantial global health burden, with its prevalence steadily rising. Understanding the importance of diabetes mellitus extends beyond its immediate health implications. It is a significant risk factor for various complications, including cardiovascular diseases, kidney disease, and vision loss. While there is no cure for diabetes, strategies like losing weight, eating healthily, being active, and receiving medical treatments can mitigate the harms of this disease in many patients. Early diagnosis can lead to lifestyle changes and more effective treatment,
the findings may contribute to the broader efforts aimed at reducing the burden of diabetes and improving public health outcomes.

### Objective of Research

In light of the increasing prevalence and associated health risks, this research aims to contribute to the early detection of diabetes mellitus. The primary objectives are twofold:

1. **Identification of Factors for Early Detection:** Investigate and identify key factors that could serve as early indicators of diabetes mellitus. This is to use for prediction of whether individual has diabetes.

2. **Association Between Important Factors:** Examine the associations between the identified factors. Understanding how these factors interact can provide insights into the complex dynamics of diabetes development.

### Dataset Description
This is a dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_012 has 3 classes. 0 is for no diabetes or only during pregnancy, 1 is for prediabetes, and 2 is for diabetes. There is class imbalance in this dataset. This dataset has 21 feature variables which composed of

HighBP: 0 = no high BP 1 = high BP
HighChol: 0 = no high cholesterol 1 = high cholesterol
CholCheck: 0 = no cholesterol check in 5 years 1 = yes cholesterol check in 5 years
BMI: Body Mass Index
Smoker: Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes] 0 = no 1 = yes
Stroke: (Ever told) you had a stroke. 0 = no 1 = yes
HeartDiseaseorAttack: coronary heart disease (CHD) or myocardial infarction (MI) 0 = no 1 = yes
PhysActivity: physical activity in past 30 days - not including job 0 = no 1 = yes
Fruits: Consume Fruit 1 or more times per day 0 = no 1 = yes
Veggies: Consume Vegetables 1 or more times per day 0 = no 1 = yes
HvyAlcoholConsump: Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week) 0 = no
AnyHealthcare: Have any kind of health care coverage, including health insurance, prepaid plans such as HMO, etc. 0 = no 1 = yes
NoDocbcCost: Was there a time in the past 12 months when you needed to see a doctor but could not because of cost? 0 = no 1 = yes
GenHlth: Would you say that in general your health is: scale 1-5 1 = excellent 2 = very good 3 = good 4 = fair 5 = poor
MentHlth: Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days was your mental health not good?
PhysHlth: Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good?
DiffWalk: Do you have serious difficulty walking or climbing stairs? 0 = no 1 = yes
Sex: 0 = female 1 = male
Age: 13-level age category (_AGEG5YR see codebook) 1 = 18-24 9 = 60-64 13 = 80 or older
Education: Education level (EDUCA see codebook) scale 1-6 1 = Never attended school or only kindergarten 2 = Grades 1 through 8
Income: Income scale (INCOME2 see codebook) scale 1-8 1 = less than $10,000 5 = less than $35,000 8 = $75,000 or more

Source of dataset: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/data

### Research Questions:
1. What are the key demographic, lifestyle, and clinical factors that could potentially serve as early indicators of diabetes mellitus?
2. What are the insights gained from the associations between the identified factors contribute understanding the development of diabetes mellitus?
