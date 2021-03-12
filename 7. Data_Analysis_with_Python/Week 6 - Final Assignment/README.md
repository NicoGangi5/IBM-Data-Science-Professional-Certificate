# Final Assignment

## Key Concepts
- Create a Jupyter notebook
- Housing price data

# Peer-graded Assignment: House Sales in King County, USA


**Question 1) Display the data types of each column using the attribute dtype, then take a screenshot and submit it, include your code in the image.**
![dtype](Q1.jpg)
![dtype](1.PNG)


**Question 2) Drop the columns "id" and "Unnamed: 0" from axis 1 using the method drop(), then use the method describe() to obtain a statistical summary of the data. Take a screenshot and submit it, make sure the inplace parameter is set to True.**
![drop id and Unnamed](Q2.jpg)
![drop id and Unnamed](2.PNG)


**Question 3) Use the method value_counts to count the number of houses with unique floor values, use the method .to_frame() to convert it to a dataframe**
![unique floors](Q3.jpg)
![unique floors](3.PNG)

**Question 4) Use the function boxplot in the seaborn library to produce a plot that can be used to determine whether houses with a waterfront view or without a waterfront view have more price outliers.**
![boxplot](Q4.jpg)
![boxplot](4.PNG)

**Question 5) Use the function regplot in the seaborn library to determine if the feature sqft_above is negatively or positively correlated with price. Take a screenshot of the plot and the code used to generate it.**
![regplot](Q5.jpg)
![regplot](5.PNG)

**Question 6) Fit a linear regression model to predict the price using the feature 'sqft_living' then calculate the R^2. Take a screenshot of your code and the value of the R^2.**
![lr sqft_living](Q6.jpg)
![lr sqft_living](6.PNG)


**Question 7) Fit a linear regression model to predict the 'price' using the list of features:**

- **"floors"**
- **"waterfront"**
- **"lat"**
- **"bedrooms"**
- **"sqft_basement"**
- **"view"**
- **"bathrooms"**
- **"sqft_living15"**
- **"sqft_above"**
- **"grade"**
- **"sqft_living"**
- **The calculate the R^2. Take a screenshot of your code and the value of the R^2.**
![mlr](Q7.jpg)
![mlr](7.PNG)

**Question 8) Create a pipeline object that scales the data performs a polynomial transform and fits a linear regression model. Fit the object using the features in the question above, then fit the model and calculate the R^2. Take a screenshot of your code and the R^2.**
![pipeline](Q8.jpg)
![pipeline](8.PNG)

**Question 9) Create and fit a Ridge regression object using the training data, setting the regularization parameter to 0.1 and calculate the R^2 using the test data. Take a screenshot for your code and the R^2**
![ridge](Q9.jpg)
![ridge](9.PNG)

**Question 10) Perform a second order polynomial transform on both the training data and testing data. Create and fit a Ridge regression object using the training data, setting the regularisation parameter to 0.1. Calculate the R^2 utilising the test data provided. Take a screenshot of your code and the R^2.**
![ridge on polynomial](Q10.jpg)
![ridge on polynomial](10.PNG)

**Share the link for your notebook:** [URL](https://colab.research.google.com/drive/1BcDs_bSxbSL4d7jqBsYsj1X0wUZlGNsz?usp=sharing)
