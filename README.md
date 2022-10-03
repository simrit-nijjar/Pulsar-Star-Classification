# DSCI 100 Group Project

This repository is a clone of the original hosted by Raikenken at https://github.com/Raikenken/dsci100project/ (Repository is private)

Created for DSCI 100 final project along with Raikenken and Iris.

## Introduction:
### Provide some relevant background information on the topic so that someone unfamiliar with it will be prepared to understand the rest of your proposal

The dataset HTRU2 describes a sample of pulsar candidates with multiple observations distinguishing between a pulsar star and a non-pulsar star. The data was collected based on the radio signals transmitted from either an actual pulsar star or random interference radio waves from space. Each observation was then classified as either an actual pulsar star, or something else entirely. Currently, these pulsar stars are used as instruments by scientists by utilizing their pulses of radiation to detect gravitational waves in the galaxy. These gravitational waves are then used to study the extreme states of matter, and find statistics of other heavenly bodies outside of the Earth’s solar system.

We will perform exploratory data analysis and visualizing using the dataset “Pulsar Star Data” retrieved online from https://archive.ics.uci.edu/ml/datasets/HTRU2

### Clearly state the question you will try to answer with your project

Based on the given variables for each observation, is the observation a pulsar star or not? Identify and describe the dataset that will be used to answer the question HTRU2.csv

We will be using every column to distinguish the “class” of each observation. The first four are simple statistics obtained from the integrated pulse profile (folded profile). This is an array of continuous variables that describe a longitude-resolved version of the signal that has been averaged in both time and frequency. The remaining four variables are similarly obtained from the DM-SNR curve.

## Methods

### Explain how you will conduct either your data analysis and which variables/columns you will use. Note - you do not need to use all variables/columns that exist in the raw data set. In fact, that's often not a good idea. For each variable think: is this a useful variable for prediction?

We will use all of the data in the dataset for our data analysis. Since each variable has a similar variable measured in a different method, we will first compare each pair of variables with respect to the classification of each observation. Afterwards, we will analyze the plots of each pair and decide to use those variables that seem to have an actual effect on the classification of each observation.

### Describe at least one way that you will visualize the results

We will be using a scatter plot to visualize the distribution of the 2 classes based on the variables that are of most importance to us based on previous tests.

## Expected outcomes and significance:

### What do you expect to find?

We expect to classify whether the body we are observing is a pulsar star based on the characteristics of the body and the radiation that it emits. What impact could such findings have? By trying to create a classification model for pulsar stars, there would be a chance to find a more accurate model to classify whether a body is a pulsar star or not. Consequently, this development would hasten the growth of science towards the outer universe which is currently light years away from us. Aside from the heavenly bodies beyond our solar system, being able to study extreme states of matter which is located light years away would allow us to learn of their properties and may give us a chance to replicate them here on earth which may bring technological advances due to their new properties.

### What future questions could this lead to?

What causes the distinct radio waves of a pulsar star?

What could the other non-pulsar star observations be besides background noise?

Are there other patterns within the data that could point to the existence of another entity we are unaware of?

