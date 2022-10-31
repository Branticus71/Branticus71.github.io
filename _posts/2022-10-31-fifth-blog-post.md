# Regression Variable Selection

When it comes to selecting variables to be included in a regression I typically follow a process like this:

## Start by envisioning the true model
Given the dependent variable what do you think the true population model would look like? What are the causal pathways between the independent variables and dependent variable?
What type of regression is needed here?

## Look through the data to see what variables match the theorized true model
If missing variables, are there any in the data that could serve as a decent proxy? Do any need to be transformed?

## Begin visualizing and exploring your data
Are there any variables that have a relationship with the outcome variable that you did not consider? What could be the cause of this relationship? Any outliers that need to be removed? Any transformations that could be done?
Is it causal, by chance, or maybe capturing the effect of another correlated variable that maybe does not exist in the data? Should quadratics and interactions be included?

## Plan the actual model
Given new information and the variables present in the data, how does this change what our regression will look like? 

## Create and refine the model(s)
Run the code to create the model and analyze at the results. Consider removing terms that are not statistically significant but only if you have a reason. 
If you came up with multiple models then compare them. Which is better at predicting on a test data set, lowest MSE, etc?

## Decide on a final model and justify it
Explain why this is the final model compared to other options. Why was a variable dropped? Why was one kept? etc.

## Acknowledge shortcomings
Any variables that should have been in the model but were not present in the data? Are any of our proxy variables sub-par? Any assumptions not holding well? Figuring out where the model falls short can improve future research into this topic/issue.
