# workshop-Multivariate-analysis

## AIM:
To Perform Multivariate Analysis

## ALGORITHM:
1.Read the given data

2.Get information from the data

3.Perform the Multivariate Analysis

4.Save the clean data to file

## PROGRAM:

import pandas as pd

df=pd.read_excel("/content/FlightInformation (1).xlsx")

df.head()

df.dtypes

import seaborn as sns

sns.scatterplot(x=df['Total_Stops'],y=df['Price'],data=df)

sns.barplot(x=df['Source'],y=df['Price'],data=df)

df.corr()

## OUTPUT

![image](https://user-images.githubusercontent.com/103020162/229982976-0f9a8276-d339-419a-acdd-bfe2b5df5dcf.png)

![image](https://user-images.githubusercontent.com/103020162/229984253-e12f5808-f797-4b2a-b62e-2465a98b243b.png)

![image](https://user-images.githubusercontent.com/103020162/229984354-68b9d09d-b4e4-4965-a947-55e985ff06aa.png)

![image](https://user-images.githubusercontent.com/103020162/229983161-53df9bad-8cca-4558-8073-9e9f2298c488.png)

![image](https://user-images.githubusercontent.com/103020162/229983731-c54d8f8d-8530-4568-9354-7bc0a4dce427.png)

![image](https://user-images.githubusercontent.com/103020162/229983830-565458d6-0be7-4ade-ab58-cb5d13cf95a4.png)

![image](https://user-images.githubusercontent.com/103020162/229983924-11fdc231-e034-46e5-903b-b69b8628cb2a.png)


## RESULT:
Thus, Bivariate/Multivariate Analysis is performed successfully.
