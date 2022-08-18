# Python-Basic-Statistics-Hypothesis-Testing

Name of the Project

Basic-Statistics-Hypothesis-testing 

Tool used for analysis 

•	Python

Packages

•	NumPy
•	Pandas
•	Matplotlib
•	Seaborn
•	SciPy
•	Scikit-Learn

Business Problem 

•	Total five different types of Business problems are addressed 

Discussion 

A Hypothesis Test helps in making a decision as to which mutually exclusive statement about the population is best supported by sample data.

Terminology used for Hypothesis Testing

Null Hypothesis (H0) – It is a statement that is commonly accepted or is considered to be the status quo. It is assumed that the observed result is due to the 
chance of factor. It is denoted by H0. If it is a test of means then we say that H0: µ1 = µ2, which states that there is no significant difference in the 2 population 
means.

Alternate Hypothesis (H1 or Ha) – As previously mentioned that Null Hypothesis and Alternate Hypothesis are mutually exclusive statements. So, if the Null 
Hypothesis is commonly accepted facts, then the Alternate Hypothesis is a real fact-based on observation from the sample data. It is denoted by H1 or Ha. If it is a 
test of means then we say that H1: µ1 ≠ µ2, which states that there is a significant difference in 2 population means.

Critical Region – The critical region is defined as the region of values in distribution that leads to the rejection of the null hypothesis at some given probability 
level.

One-Tailed Test – A one-tailed test is a statistical hypothesis test in which the critical area of distribution is either greater than or less than a certain value, 
but can’t be both. For this the alternate hypothesis formulation is H1 : µ1 > µ2  or  H1 : µ1  < µ2 .

Two-Tailed Test – A two-tailed test is a statistical hypothesis test in which the critical area of distribution is on either of the sides. It tests whether the sample 
means of 2 or more populations are unequal (in the test of means). For this alternate hypothesis, the formulation is H1: µ1 ≠ µ2.

In either of the above 2 tests if the sample tested falls in the critical region than the alternate hypothesis holds to be true and the null hypothesis is rejected. 
The alternate hypothesis is made as a conclusive observation for the population-based on sample data.

![image](https://user-images.githubusercontent.com/111371078/185462168-3d0d11e3-6143-4de7-b92a-5b9e09008a8c.png)

 
Types of Test Statistics

Test Statistics measure how close the sample has come to the null hypothesis. This observation differs from a random sample to a sample. 
A test statistic results contain insights about the data that helps in making the decision of whether to reject the null hypothesis or not. There are different 
probability models for different types of populations. Based on probability distribution different hypothesis tests are selected. Sample data is like a mirror image 
for the population. So, the sample data must provide sufficient evidence to reject the null hypothesis and conclude that the effect exists in the population. If it is
not able to do so then effect doesn’t exist in the population and thus we would fail to reject the null hypothesis. Nothing comes with perfection and so does data 
insights. If everything is perfect and with 100% accuracy then it is something overfitted or manipulated. It is not natural. If things are natural and robust then 
they come with a cost attached to it in the form of error. Therefore, we have error terms here. Let’s get to know these terms.

Error terms in hypothesis testing

Type-I error – This error occurs when insights drawn from sample data lead to rejection of the null hypothesis even when it is true. 
This error could be controlled as it has direct bearing with a level of significance.

Type-II error – This error occurs when insights from sample data result in failing to reject the null hypothesis although it is false. 

Level of Significance – It is the probability of making type I error and is denoted by α. It is the maximum probability of making type I error. 
As per standard for 95% confidence level value of alpha is 0.05. This means that there is a 5% probability of making type I error or rejecting the 
null hypothesis even when it is true.

p-value – It is a statistical concept that is used from hypothesis testing to regression to tree models and much more. It is an integral part of data science. 
If the p-value is high there are higher chances of the null hypothesis being true and if the p-value is low then it is more likely to reject the null hypothesis. 
The Standard p-value is equal to alpha and is used for checking statistical p-value against it and making the decision.

High P-Values: Your data are likely with a true null

Low P-Values: Your data are unlikely with a true null

Now since we have been pretty much acquainted with basic terminology used in hypothesis testing, let’s see how to use it in making business decisions. 

Steps followed are as below:

1.	Formulate the Null and Alternate Hypothesis

2.	Based on data and probability distribution select the hypothesis test to be performed

3.	Based on the business are and problem statement selects the level of significance if 0.05 (standard alpha) is not acceptable.

4.	Calculate test statistics on the sample data collected

5.	Calculate the p-value

6.	Based on p-value draw insights to reject or fail to reject the null hypothesis

7.	Draw your business conclusion.

If the above basic steps are performed in said sequence, then the valuable business decisions could be made in no time and with precision. This method has 
helped many pharmaceutical drugs and medical procedures in testing.
