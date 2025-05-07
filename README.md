# DIABETES-ANALYSIS-PREDICTION-2024

Diabetes is a chronic metabolic disorder, characterized by elevated blood sugar, high triglyceride levels and an increased metabolic rate. In this analysis the goal would be analyse certain factor that can influence blood sugar levels, these factors; Age, Blood pressure, Diet type, Medication use, Triglyceride level, Pregnancies’, Waist circumference, Hip circumference, Hypertension, Family history, Family history, Waist Hip Ratio, HbA1c, Low Density Lipoprotein (LDL), High Density Lipoprotein (HDL), Outcome.

Story of data: This dataset is from the public domain of Kaggle.com, which is an online repository of data stores. The data is structured in rows and columns, with the columns having these values: Age, Blood pressure, Diet type, Medication use, Triglyceride level, Pregnancies, Waist circumference, Hip circumference, Hypertension, Family history and more. The factor list above represents some of the risk factor to Diabetes, they contribute directly or indirectly to the conditions, seen since time memorial. The dataset tells us the following:

![Screenshot 2025-03-20 082121](https://github.com/user-attachments/assets/2d74b9be-8843-4f10-8b0e-11754da55b49)

Sugar and diabetic status of people across different age groups

Effect of medication use on blood sugar level

The relationship between LDL, HDL and triglyceride levels in the body

Family history and diabetes

Limitations were the fact that no year or date of data collection, no status report of whether the individual had, or previously had diabetes or elevated sugar levels.

Data splitting and preprocessing:

Data cleaning: The dataset was cleaned upon download from Kaggle, I checked consistency, duplicates, missing values, blanks row & columns.

Data Transformations: To enable swift analytical process, the dataset was transformed from normal excel table into a standard excel table, this enables proper colour usage on the table and also automate the table.

Data splitting: the dataset was splatted into dependent and independent data category based on their ability to have a separate existence. Dependent data; HbA1c, Low Density Lipoprotein (LDL), High Density Lipoprotein (HDL), Outcome. Independent data; Age, Blood pressure, Diet type, Medication use, Triglyceride level, Pregnancies’, Waist circumference, Hip circumference, Hypertension, Family history, Family history, Waist Hip Ratio.

Industry context: Healthcare and wellness.

Industry stakeholders: Pharmacist, Pharmaceutical companies, Governments, Physicians, Healthcare Practitioner’s, and Individuals.

Value to the Industry: Reducing incidence of high blood sugar level leading reduced diabetes and keeping diabetic patient stable while reduce crisis and complication.

![Screenshot 2025-03-20 084746](https://github.com/user-attachments/assets/c10e8950-4022-4a9b-abb3-f7f079801a56)

Pre-analysis:

Potential Analysis/ Questions

1. what are the susceptible ages to high blood sugar level?

2. who those with high cholesterols?

3. Family history and blood sugar level?

4. what is the Implication of high BMI?

5. What diet mean to diabetes person?

6. what are the most susceptible age to diabetes?

7. what is hypertension effect on blood sugar level

8. HbA1c by age

9. Blood sugar level in relation to HbA1c

Potential Insights

1. We could derive how LDL, HDL and triglycerides affect blood sugar level

2. We will finetune how family history can tell us who will possibly have diabetes

3. We would derive susceptible ages to diabetes

4. It can also be deduced from the data how diets affect blood sugar level

5. We will know if having hypertension can cause diabetes

6. How BMI relates diabetes or high sugar level

7. The implication of high cholesterol

![Screenshot 2025-03-20 084811](https://github.com/user-attachments/assets/8dce486d-a8e2-40bd-bc22-9760050a625a)

In-analysis:

1. With 6653 persons’ family has no history of high blood glucose level, while 2885 persons had a family history of high blood sugar level, the history of blood glucose level can be said to be a significant factor.

2. Triglycerides have a great impact on the diabetes status because it is a cumulative normal blood sugar level overtime.

3. Pregnancies number per sum 0–4 at 889, 5–9 at 867, 10–14 at 787, and 15–19 at 342, respectively.

4. WHR at 1.22–132 was 110.31, at 1.12–1.22 was 110.18, at 1.02–1.12 was 108.90, vat 0.92–1.02 was 108.17,1.32–1.42 was 107.19 waist to hip ratio does not really pose diabetic treat.

5. Blood relation to blood glucose level 100–109 at 121.99, 90–99 at 115.12, 80–89 at 106.90, 70–79 at 98.06 and 60–69 at 87.75

6. HDL based on blood glucose concentration 100–110 had 124.30, 0 had 118.63, 90–100 had 108.78, 0–10 at 108.10, 10–20 at 107.39.

7. BMI — blood glucose level as illustrated below: 39.69 at 189.1, 40.27 at 1779.7,46.66 was 177.3, 177.1 at 44.56 and 24.24 at 172.1

8. Age and blood glucose level 75–89 having 121.15, 60–74 at 112.72, 45–59 at 105.52, 30–44 at 97.25 and 15–29 at 90.72.

9. BMI increase is a risk factor for high blood glucose level.

10. High blood sugar level is a determinant for obesity, diabetes.

Technique used: Pivot tables and chart were used for this analysis.

Post-analysis and insights:

Key finding: Age, BMI, high blood pressure, elevated LDL, and past history of high blood sugar level are key risk factors in diagnose high blood sugar and the risk of diabetes.

Data visualization & charts:

![image](https://github.com/user-attachments/assets/c46a3413-f0b4-4142-bdac-581c0429eaa5)
![image](https://github.com/user-attachments/assets/526fa89d-ee12-48ef-a1c1-397b931bda4e)
![image](https://github.com/user-attachments/assets/44931fe0-8cbb-4784-9a25-fdcdc2c9c7fa)
![image](https://github.com/user-attachments/assets/80cffacc-b90b-4d05-ac2a-0f5de9a457d4)
![image](https://github.com/user-attachments/assets/1df13231-b049-4ffd-9ff5-4f062b1a120c)
![image](https://github.com/user-attachments/assets/61759b68-9f66-4286-b9d9-4df99e16dc18)
![image](https://github.com/user-attachments/assets/e629d85b-2349-4203-9248-1b139cab1b15)
![image](https://github.com/user-attachments/assets/6174f0aa-a793-4843-a04a-3631d009483b)

Chart 9: ANALYTICAL DASHBOARD FOR DIABETICS PREDICTION

Recommendations and observation:

Analysis Observations

It was observed that 6653 persons’ family has no history of high blood glucose level, while 2885 persons had a family history of high blood sugar level

It was observed that the triglyceride level for the patient whose family has no history of high blood sugar was the following: TGL 15–29 was 153.55, 75–89 was 152.25, 60–74 was at 45–59, and 30–44 was at 149.70.

The observation also shows the number of pregnancies based on blood sugar levels for people with 0) zero history of diabetes: 0–4 at 889, 5–9 at 867, 10–14 at 787, and 15–19 at 342, respectively. WHR at 1.22–132 was 110.31, at 1.12–1.22 was 110.18, at 1.02–1.12 was 108.90, vat 0.92–1.02 was 108.17,1.32–1.42 was 107.19

Observation shows that those with higher blood pressure also had higher blood sugar: 100–109 at 121.99, 90–99 at 115.12, 80–89 at 106.90, 70–79 at 98.06 and 60–69 at 87.75. HDL based on blood glucose concentration 100–110 had 124.30, 0 had 118.63, 90–100 had 108.78, 0–10 at 108.10, 10–20 at 107.39.

It was observed that in the case of BMI, not all who had high BMI had high blood glucose as illustrated below: 39.69 at 189.1, 40.27 at 1779.7,46.66 was 177.3, 177.1 at 44.56 and 24.24 at 172.1

Observed from the analysis that age is a factor; it was noticed that those with higher age had higher blood glucose with 75–89 having 121.15, 60–74 at 112.72, 45–59 at 105.52, 30–44 at 97.25 and 15–29 at 90.72.

It was observed that 1052 persons family has no history of high blood glucose level while 489 persons has a family his of high blood sugar level. It was observed that the triglyceride level for the patient whose family has no history of high blood sugar and who had the following TGL 15–29 was 153.

Observation also shows a number of pregnancies based on blood sugar level for people with different ages: 0–4 at 91.22, 5–9 at 91.06,10–14 at 90.83 and 15–19 at 89.66, respectively. WHR at 1.22–132 was 91.67, at 1.12–1.22 was 93.9, at 1.02–1.12 was 95.02, at 0.92–1.02 was 108.17,1.32–1.42 was 97.90

Observation shows that those with higher blood pressure also had higher blood sugar: 100–109 at 103.82, 90–99 at 101.95, 80–89 at 99.27, 70–79 at 90.31 and 60–69 at 80.41. HDL based on blood glucose concentration 100–110 had 124.30, 0 had 118.63, 90–100 had 108.78, 0–10 at 108.10, and 10–20 at 107.39.

It was observed that in the case of BMI, not all who had high BMI had high blood glucose as illustrated below: 39.69 at 189.1, 40.27 at 1779.7,46.66 was 177.3, 177.1 at 44.56 and 24.24 at 172.1

Observed from the analysis that age is a factor; it was noticed that those with higher age had higher blood glucose, with 75–89 having 121.15, 60–74 at 112.72, 45–59 at 105.52, 30–44 at 97.25 and 15–29 at 90.72. Those with 0–4 number of pregnancies had an average blood glucose level of 105.64

It was observed that triglyceride level for patient with higher age had high blood sugar, the following TGL 15–29 was 152.71, 75–89 had 152.55, 60–74 was at 149.87, 149.06 was for 45–59 and 30–44 at 147.89.

Observation also shows number of pregnancies at 107.89 when the triglycerides level 250–300 this was for those that had pregnancy 0–4. WHR at 1.22–132 was 110.31, at 1.12–1.22 was 110.18, at 1.02–1.12 was 108.90, at 0.92–1.02 was 108.17,1.32–1.42 was 107.19

Observation shows that those with higher blood pressure also had higher blood sugar 100–109 at 121.99, 90–99 at 115.12, 80–89 at 106.90, 70–79 at 98.06 and 60–69 at 87.

![Screenshot 2025-03-20 082611](https://github.com/user-attachments/assets/36dbff63-4645-4ac3-a511-8a7070360bda)

RECOMMENDATION

1. Age is a huge factor, as we have seen from the chart about blood glucose levels, so it is recommended that as age progresses, individuals should be advised to avoid food & drinks that trigger high blood glucose levels.

2. Blood glucose level was also seen to rise as the blood pressure rose, so it is recommended that those with high blood pressure should control or pay close attention to their blood glucose level to complication such as organ failure.

3. Increased BMI led to increase Diabetic chances so recommendation would be that emphasis be placed on weight loss program.

4. WHR also contributed significant portion to the diabetic risk so measures should be taken to cut it down especially in obese patient.

5. Recommendation is that pregnant women should take appropriate steps to manage their diabetes status by controlling sugar blood level through appropriate dieting.

6. At the normal blood glucose level HDL seem to be low so recommendation is that external sources be introduced to boost the level to avoid diabetes and cardiovascular accident.

7. Family history played a major role in the blood glucose level as such the family with history of high blood glucose level should sensitize their siblings for better health.

![Screenshot 2025-03-20 084712](https://github.com/user-attachments/assets/c762edf6-d5c8-4ad7-9524-835a7b74c2f9)

Conclusion:
Blood glucose or sugar is a measure of the amount of sugar in the blood of any given individual and it can be measured as random blood sugar or fasting blood sugar level. So, this analysis was checking food different values and risk factors that influence a person’s blood glucose/ sugar, some of the very important among them based on the analysis report are Age, high density lipoprotein, low density lipoprotein, hypertension status, body mass index, so individuals with elevated values of any of the above indices should endeavor to monitor very closely and ensure all vitals are ok. The analysis could be seen from the limitation in the data set such as limited data on the year these, data on individual person’s eating habit weren’t given as such future research could be chart toward dieting, other predisposing condition.
