# Student CGPA
CGPA of Students

**The dataset is available with the owner**

```Updated once in a year (No longer updated; however feel free to use the code and add your own data)```

- Currently it has only the data of 1317 students. 
- With each new set of I, II, and III semester CGPA data, the data would increase. 

This would help to determine if a trained model can predict the scores of the students. 
Currently, it assumes the CGPA of the students are known for the first and second semester and tries to predict the CGPA at the end third semester. It shows promising results.

Later this would be improved (hopefully) with time to more semesters as data accumulates.  
For detail code and results [Click Here](https://colab.research.google.com/drive/1B08kfES8J8C48FO_fWYqc2YeraLErkXi?usp=sharing)  
|Regressor|Best score obtained|
|:----------------:|:----------------:|
|Random Forest (n_estimators=600)|0.9346|
|Support Vector (kernel=rbf, gamma=scale)|0.9444|
|Polynomial (degree = 3)|0.9480|
