# Multi-label Classification Project
This is a repository on my multi label classification project on the Costa-rican-household-poverty-prediction dataset where we have to predict the hoursehold type of the families based on a select set of features.

You can find the dataset here : https://www.kaggle.com/c/costa-rican-household-poverty-prediction

This dataset has very high dimensionality with 143 different columns.
It is a multi-label classification problem with 4 labels:
1.	Extereme Poverty
2.	Vulnerable
3.	Moderate Poverty
4. NonVulnerable

It is also **an instance of imbalanced classes** due to a skew towrds the 4th label, i.e. the NonVulnerable class as is evident from the following graphic:

![download](https://user-images.githubusercontent.com/53376072/78048749-d213f280-7397-11ea-860c-9b2d16a6012e.png)


## Salient features of the Project

### (1.) Pandas Profiling report:
Pandas pp report completely changed the way I looked at my data and saved me a lot of time by performing state of the art EDA on each column of the dataset individually and also on the entire dataset as a whole.Besides performing EDA, it also automatically gives you suggestions regarding missing values, high cardinality and high colinearity among the columns.

![Pandas profiling report](https://user-images.githubusercontent.com/53376072/78123992-a858db00-742c-11ea-8159-ecd46f967e99.JPG)



### (2.) Use of masks to remove correlated columns:

![Removing correlated columns](https://user-images.githubusercontent.com/53376072/78124293-1ac9bb00-742d-11ea-9aeb-22300a10f6d9.JPG)

### (3.) Removing columns with % of missing values greater than a specified threshold:

![Removing columns with missing values](https://user-images.githubusercontent.com/53376072/78124598-87dd5080-742d-11ea-86a6-adfb03586844.JPG)

### (4.) Using PCA for Dimentionality Reduction:

![Using PCA for dimentionality reduction](https://user-images.githubusercontent.com/53376072/78124742-bbb87600-742d-11ea-9e90-d3871445ae10.JPG)

### (5.) Using OOP for efficient model deployment:

Use of classes helped me streamline and aggregate multiple steps of model deployment.

![Using OOP for model deployment](https://user-images.githubusercontent.com/53376072/78125266-6892f300-742e-11ea-943e-c0692e039e72.JPG)

### (6.) Configuring ML models to handle imbalanced classes:

![Configuring algoirthms to make them handle imbalanced classes better](https://user-images.githubusercontent.com/53376072/78125554-d3dcc500-742e-11ea-840a-eff0db78b482.jpg)

