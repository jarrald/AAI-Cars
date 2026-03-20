# AAI-Cars
Mandatory assignment for AAI Elective on SD 2026 1st semester.


# Abstract
# Introduction
# Research Question/Problem Formulation
# Classification problem
We want to measure if we can determine the origin of a car from it’s other features. The dataset include the following features:
    • mpg
    • cylinders
    • horsepower
    • weight
    • acceleration
    • model
    • year
    • origin
    • car name
We’re using origin as our ground truth and target value.
Observe that origin is either America, Asia and Europe. We have determined this from the car brands originating from the respective regions in the world.
There’s an issue with the dataset because the statistical distribution is not even. American cars are over represented in the dataset, they account for over 60% of the total cars. Therefore we have decided to penalize mistakes on minority classes more.
Because the dataset is very small, around 400 entries, we decided to not use a Deep Neural Network model.
Instead we can use Decision Trees, Random Forests and other models that perform better on small datasets, this means we can evaluate the fitness of the models fast. We will try different combinations of features to determine which features contribute to a more fit model.
Regression problem
We want to use the above data again here and see if we can predict acceleration from the other features. Here we will use different models more fit for regression problems, such as linear regression. The most interesting features here are cylinders, mpg, horse, weight.
We can use some cost functions to see how our model performs. We will also evaluate the different metrics such as f-score, accuracy and a few others perhaps.

# Methods
# Analysis
# Findings
# Conclusion