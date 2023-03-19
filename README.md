# Breast-Cancer-Classification-using-Machine-Learning
Breast Cancer Classification using Machine Learning
Topic: Breast cancer Classification 



Features Information:



1) ID number 

2) Diagnosis (M = malignant, B = benign) 3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)

 b) texture (standard deviation of gray-scale values) 

c) perimeter 

d) area 

e) smoothness (local variation in radius lengths) 

f) compactness (perimeter^2 / area - 1.0) g) concavity (severity of concave portions of the contour) h) concave points (number of concave portions of the contour)

 i) symmetry 

j) fractal dimension ("coastline approximation" - 1)

j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three

largest values) of these features were computed for each image,

resulting in 30 features. For instance, field 3 is Mean Radius, field

13 is Radius SE, field 23 is Worst Radius.





Insights: 



Missing values : 0

No of columns: 31

Shape :(569, 32)

Target:

B    357

M    212

Skewness : Right Skewed 

Model Used : Logistic Regression

testing accuracy : 85%

training accuracy :91%
