# Capstone_Project_Data_scientist - Facies (Lithology rock type) Classification using Machine Learning
## Project Definition
For this project I decided to analyse and using ML to predict the facies (lithology rock type) in oil&gas field from the wells data that drilled, and predict for other wells based on the model. Facies is very important indicator for interpreter to determine where is oil and gas, and there are some challenge when not enough data of rock sampling, so base on the other data and apply ML approach is one of the good way to interpret/predict for Facie lithology rocktype. Below is some of figuring out the problem we will approach in this study:

- Project Overview: Facies classification is one of the most important tasks that geoscientists work on development and exploration projects. Sedimentary facies reflect particular physical, chemical, and biological condition that unit experienced during sedimentation process. Facies/lithofacies is a key important factor to determine oil&gas accumulation. In this project, using the 4 wells data with well logs dataset, and based on this data I will do analyst and making the model to predict the facies - lithology rocktype for another wells
- Problem Statement: In this study, it is practiced to train machine learning algorithms (Neural Network) to predict facies from well log data, base on the data of continious logs: NPHI, RHOB, VCL, DT & and descrete log: Facies, to make a mmodel for future Facies forcast for another well without Facies interpretation.
- Metrics: In this project, as classificationn approach,so we used performance metrics as precision, recall, and F1-Score

## Installation
There are some neccessary library nees to install such as:
- numPy
- pandas
- matplolib
- Seaborn
- sklearn
The code should run with no issues using Python versions 3
 
 ## Project Motivation 
For this project, I was interestested in using the csv file of 4 wells dataset to better understand and figure out the problem:

- Exploration Data Analysis to understand about the distribution of lithology rocktye?
- Data analysis to understand about the correlation between the others parameter with lithofacies?
- Machine learning approach to predict litho facies for the well (test_well)
- The evaluation and result of prediting model

## File Descriptions
There are 1 notebooks available here to show all of works related to problem I rised. It will explore searching through the data pertaining to the questions showcased by the notebook title. Markdown cells were used to assist in walking through the thought process for individual steps.
02 dataset: Data_ANN.csv, test_well_4.csv


## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@NguyenKhoaLamTrinh/apply-machine-learning-model-neural-network-to-classify-the-facies-lithology-rock-type-8dca8fb37820).
