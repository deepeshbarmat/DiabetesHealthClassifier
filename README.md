# Diabetes Health Classifier
This project does a comparison of different Classification algorithms on Health Data Indicators to determine Diabetes in a patient.


### Dataset Overview

The target feature is Diabetes_binary, which is a binary classification variable:
- 0: Respondent has no diabetes.
- 1: Respondent has prediabetes or diabetes.</br>
#### Features:
The dataset includes 21 feature variables, representing demographic, behavioural, and health-related factors. These features are as follows: 

</br>
<table>
    <tr>
        <td>Feature</td>
        <td>Type</td>
        <td>Demographic</td>
        <td>Description </td>
    </tr>
    <tr>
        <td>HighBP</td>
        <td>Binary</td>
        <td></td>
        <td>0 = no high BP, 1 = high BP. </td>
    </tr>
    <tr>
        <td>HighChol</td>
        <td>Binary</td>
        <td></td>
        <td>0 = no high cholesterol, 1 = high cholesterol. </td>
    </tr>
    <tr>
        <td>CholCheck</td>
        <td>Binary</td>
        <td></td>
        <td>0 = no cholesterol check in 5 years, 1 = yes cholesterol check in 5 years. </td>
    </tr>
    <tr>
        <td>BMI</td>
        <td>Integer</td>
        <td></td>
        <td>Body Mass Index. </td>
    </tr>
    <tr>
        <td>Smoker</td>
        <td>Binary</td>
        <td></td>
        <td>Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes] 0 = no, 1 = yes. </td>
    </tr>
    <tr>
        <td>Stroke</td>
        <td>Binary</td>
        <td></td>
        <td>(Ever told) you had a stroke. 0 = no, 1 = yes. </td>
    </tr>
    <tr>
        <td>HeartDiseaseorAttack</td>
        <td>Binary</td>
        <td></td>
        <td>coronary heart disease (CHD) or myocardial infarction (MI) 0 = no, 1 = yes. </td>
    </tr>
    <tr>
        <td>PhysActivity</td>
        <td>Binary</td>
        <td></td>
        <td>physical activity in the past 30 days - not including job 0 = no, 1 = yes. </td>
    </tr>
    <tr>
        <td>Fruits</td>
        <td>Binary</td>
        <td></td>
        <td>Consume Fruit 1 or more times per day 0 = no, 1 = yes. </td>
    </tr>
    <tr>
        <td>Veggies</td>
        <td>Binary</td>
        <td></td>
        <td>Consume Vegetables 1 or more times per day 0 = no, 1 = yes. </td>
    </tr>
    <tr>
        <td>HvyAlcoholConsump</td>
        <td>Binary</td>
        <td></td>
        <td>Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week) 0 = no, 1 = yes. </td>
    </tr>
    <tr>
        <td>AnyHealthcare</td>
        <td>Binary</td>
        <td></td>
        <td>Have any health care coverage, including health insurance, prepaid plans such as HMO, etc. 0 = no, 1 = yes. </td>
    </tr>
    <tr>
        <td>NoDocbcCost</td>
        <td>Binary</td>
        <td></td>
        <td>Was there a time in the past 12 months when you needed to see a doctor but could not because of cost? 0 = no, 1 = yes. </td>
    </tr>
    <tr>
        <td>GenHlth</td>
        <td>Integer</td>
        <td></td>
        <td>Would you say that in general, your health is: a scale 1-5 1 = excellent, 2 = very good, 3 = good, 4 = fair, 5 = poor. </td>
    </tr>
    <tr>
        <td>MentHlth</td>
        <td>Integer</td>
        <td></td>
        <td>Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days was your mental health not good? scale 1-30 days. </td>
    </tr>
    <tr>
        <td>PhysHlth</td>
        <td>Integer</td>
        <td></td>
        <td>Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good? scale 1-30 days. </td>
    </tr>
    <tr>
        <td>DiffWalk</td>
        <td>Binary</td>
        <td></td>
        <td>Do you have serious difficulty walking or climbing stairs? 0 = no, 1 = yes. </td>
    </tr>
    <tr>
        <td>Sex</td>
        <td>Binary</td>
        <td>Sex</td>
        <td>0 = female, 1 = male. </td>
    </tr>
    <tr>
        <td>Age</td>
        <td>Integer</td>
        <td>Age</td>
        <td>13-level age category (_AGEG5YR see codebook) 1 = 18-24, 9 = 60-64, 13 = 80 or older. </td>
    </tr>
    <tr>
        <td>Education</td>
        <td>Integer</td>
        <td>Education Level</td>
        <td>Education level (EDUCA see codebook) scale 1-6 1 = Never attended school or only kindergarten, 2 = Grades 1 through 8 (Elementary), 3 = Grades 9 through 11 (Some high school), 4 = Grade 12 or GED (High school graduate), 5 = College 1 year to 3 years (Some college or technical school), 6 = College 4 years or more (College graduate). </td>
    </tr>
    <tr>
        <td>Income</td>
        <td>Integer</td>
        <td>Income</td>
        <td>Income scale (INCOME2 see codebook) scale 1-8 1 = less than $10,000, 5 = less than $35,000, 8 = $75,000 or more. </td>
    </tr>
</table>


### Models:
-  K-Nearest Neighbours
-  Decison Trees
-  Logisitic Regression
-  Naive Bayes
-  Linear Discriminatnt Analysis
-  Random Forest
-  Artificial Neural Network
