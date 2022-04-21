Comparisons of different machine learning algorithms predicting whether someone has heart disease from 14 biological attributes.

The maximum accuracy is 90%, achieved using the Random Forest classifier algorithm
Biological Features
Features used for training machine learning models on, including the special binary class label target, describing whether heart disease was detected.

1.age: Age in years

2.ca: Number of major blood vessels (0-3)

3.chol: Serum cholestrol in mg/dl

4.cp: Chest pain type

  -Value 1: Typical angina
  
  -Value 2: Atypical angina
  
  -Value 3: Non-anginal pain
  
  -Value 4: Asymptomatic
  
 5.exang: Exercise induced angina (1 = yes; 0 = no)

 6.fbs: fasting blood sugar > 120 mg/dl (1 = true; 0 = no)

 7.oldpeak: ST depression induced by exercise relative to rest

 8.restecg: Resting electrocardiographic results

   -Value 0: Normal
   
   -Value 1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
   
   -Value 2: Showing probable or definite left ventricular hypertrophy by Estes' criteria
   
 9.sex: Sex (1 = male; 0 = female)

 10.slope: The slope of the peak exercise ST segment

   -Value 1: Upsloping
   
   -Value 2: Flat
   
   -Value 3: Downsloping
   
  11.target: Heart disease detection (0 = disease; 1 = no disease)

  12.thal: Thalium stress test

   -Value 3: normal
   
   -Value 6: fixed defect
          
   -Value 7: reversibe defect

   
  13.thalach: Maximum heart rate achieved in bpm

  14.trestbps: Resting blood pressure (in mmHg on admission to the hospital)

Data Preprocessing
-The following data preprocessing methods are used
-A correlation matrix and histograms of the distributions of attributes are also generated.

Machine Learning Algorithms
The machine learning algorithms used

1.Logistic Regression (Scikit-learn)
2. Naive Bayes (Scikit-learn)
3. Support Vector Machine (Linear) (Scikit-learn)
4. K-Nearest Neighbours (Scikit-learn)
5. Decision Tree (Scikit-learn)
6. Random Forest (Scikit-learn)
7. XGBoost (Scikit-learn)

Best Accuracy: 90% (Random Forest)

Dependencies are:

Python 

Pandas

NumPy

Scikit-Learn

Matplotlib

Seaborn

