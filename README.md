# Automated Personality Type Prediction using Myers-Briggs Type Indicator

My focus is using Deep Learning tools to improve upon previous attempts at classifying personality type from written text. I am using the Myers-Briggs Personality Type Indicator, which is one of the more widely used today for practical applications that range from hiring to counseling. I test a variety of models to find an optimal approach. In the end, I was able to outperform the previous works with a binary classification model for the 4 categories of personality, using a sigmoid activation function and cross entropy as my loss. Average accuracy across the 4 categories is 84%.

## Files

### Executables
- data_processing.ipynb - processes the data and outputs features to csv files
- vectorized_posts_largeSet - csv file w feature space - 1000
- moded1.ipynb - model 1 source code - single layer neural network (keras sequential) 
- model2.ipynb - model 2 sources code - single layer neural netowrk (keras general model)
- scs_binary_model2and3.ipynb - model 3 source code - 4 separate binary classifiers

### Data
- vectorized_posts3 - csv file w feature space = 500 (produced by data_processing.ipynb)
- vectorized_posts_largeSet - csv file w feature space - 1000 (produced by data_processing.ipynb)

### Analysis
- Analysis_MBTI_Detector.pdf

## To Run
- You do not need to run 'data_processing.ipynb' if you use the files it generates. These contain the downloaded and processed feature spaces for both the 500 feature space size, and the 1000 (vectorized_posts3 / vectorized_posts_largeSet)
- You will however need to download the gaggle dataset, as the model files extract the targets from there -> [myers briggs dataset](https://www.kaggle.com/datasnaek/mbti-type)
- Each of the remaining 3 notebook files should be uploaded into jupyter notebooks and run from there

Language: python3
