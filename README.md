# Neural_Network_Charity_Analysis

## Overview

Create a binary classifier that is capable of predicting whether applicant organizations will be successful if funded by Alphabet Soup.

Tools:

- Jupyter Notebook, Python with SKLearn, TensorFlow, and OneHotEncoder

## Results

The original test model yielded a loss of 56% and an accuracy of 72%, as shown below.

Original test model

![image](https://user-images.githubusercontent.com/78892035/125198778-498a3000-e231-11eb-920f-5276f2651db3.png)


In an attempt to improve the model's results a third layer was added, the output was changed from “sigmoid” to “relu,” and the income column was regrouped. See individual outcomes below:

Adding third layer test:

For the optimization model, I added a third layer on top of the two initial ones. The provided code suggested 80 and 30 neurons, the third layer added 10.

![image](https://user-images.githubusercontent.com/78892035/125200358-b94fe900-e238-11eb-9ef8-873feb10a139.png)

![image](https://user-images.githubusercontent.com/78892035/125200304-755ce400-e238-11eb-82b3-7abba0ccf69f.png)

New output method test:

![image](https://user-images.githubusercontent.com/78892035/125200583-c5887600-e239-11eb-8695-71a88b4da679.png)

Clean Income column test:

![image](https://user-images.githubusercontent.com/78892035/125201319-99222900-e23c-11eb-94d6-2409703e5098.png)



Final output using all 3 tests:

![image](https://user-images.githubusercontent.com/78892035/125201575-ca4f2900-e23d-11eb-8522-74dd63900ae4.png)

## Summary

Little improvment to accuracy: 

With the changes, the model not able to achieve the targeted performance of 75%. The top reading was consistently 73%. The Random Forest model ran with 71% accuracy, suggesting that perhaps the data set needs to be inspected and cleaned further.




