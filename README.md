# Neural_Network_Charity_Analysis
# Overview of the analysis. We will use machine learning and neural networks to see if we can predict whether applicants will be funded by Alphabet Soup.
# Results 
## The target variable is whether the application is successful.
## Features represent a measurable piece of data that can be used for analysis. Some of the feautures in this model are ask amount, apllication type and income amount.
## We removed the EIN and name columns from the datset becuse they are not beneficial to the model.
## The model has three layers with 80, 30 and 1 neurons for a total of 111. The model has two application functions, relu and sigmoid.
## I was unable to get the model to run above 75%. I tried changing some of the binning varaibles, classification replacement counts, number of neurons and number of epochs but to no avail. I have the outputs at the bottom of the optimization code.
## Summary. At 73% the model is not spectacular and would certainly need some improvement. To achieve better results we could add layers and neurons to see if that would help.
