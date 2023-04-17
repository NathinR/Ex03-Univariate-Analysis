# Ex03-Univariate-Analysis

# Aim
To read the given data and perform the univariate analysis with different types of plots.

# Explanation
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.  

# Algorithm

# Step1
Read the given data.

# Step2
Get the information about the data.

# Step3
Remove the null values from the data.

# Step4
Mention the datatypes from the data.

# Step5
Count the values from the data.

# Step6
Do plots like boxplots,countplot,distribution plot,histogram plot.

# Program: 
```
import pandas as pd
i+mport numpy as np
import seaborn as sns
df=pd.read_csv("SuperStore.csv")
print(df)
df.head()
df.info()
df.dtypes
df.describe()
sns.boxplot(x='Postal Code',data=df)
sns.countplot(x="Postal Code",data=df)
sns.histplot(x="Postal Code",data=df)
df.skew()
sns.boxplot(x="Sales",data=df)
sns.histplot(x='Postal Code',data=df)
sns.displot(x="Postal Code",data=df)
df.kurtosis()
sns.boxplot(x="Sales",data=df)
```
```
import pandas as pd
import seaborn as sns
df1=pd.read_csv("diabetes.csv")
print(df1)
df1.info()
df1.dtypes
df1.skew()
df1.describe()
sns.boxplot(x='Glucose',data=df1)
sns.countplot(x="Glucose",data=df1)
sns.displot(df1["Glucose"]) 
sns.histplot(x="Glucose",data=df1)
df1.skew()
df1.kurtosis()
sns.boxplot(x="Insulin",data=df1)
```

# Output:

![image](https://user-images.githubusercontent.com/118679646/227993265-4557f2e2-b6dd-4496-8a73-b9b365df0a15.png)
![image](https://user-images.githubusercontent.com/118679646/227994405-fa0ea7c3-beaf-4f10-bbbe-ea1fcf0293bf.png)
![image](https://user-images.githubusercontent.com/118679646/227995574-7d0fb9c2-4a6b-4470-9940-fef61800a9f6.png)
![image](https://user-images.githubusercontent.com/118679646/227995866-fc10afa2-d5e4-4118-824b-ac88fa333680.png)



![image](https://user-images.githubusercontent.com/118679646/227996697-079fd8a5-fc73-440d-9929-5e190298a0a9.png)
![image](https://user-images.githubusercontent.com/118679646/227996434-f31cbc25-9d90-4deb-93ba-9e434e87b144.png)
![image](https://user-images.githubusercontent.com/118679646/227996921-57872a04-f85b-47c2-8182-1e25253e657d.png)
![image](https://user-images.githubusercontent.com/118679646/227997150-8acf5b73-e4e2-4698-b58e-6262de63e8a9.png)
![image](https://user-images.githubusercontent.com/118679646/227997477-c0ae0c20-19fa-4ca0-be51-c04c139b6319.png)


# RESULT:
Thus we have read the given data and performed the univariate analysis with different types of plots.







