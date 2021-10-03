# Personality-Classification
This is a simple Logistic Regression for classifying the Big Five personality label from customer's review text.
## Data Statistics: 
There are 990 users in this dataset. Each user contains at least 350 words review text. Each user contains a Big Five personality scores.

Label of each personality class: 
> 0: 'agreeableness'
> 1:'conscientiousness'
> 2: 'neuroticism'
> 3: 'extraversion'
> 4: 'openness' 

Number of each personality class: 
> 0: 628
> 1: 57
> 2: 40
> 3: 113
> 4: 52

## Data Preprocessing:
Word2Vec 300d.

## Traning/Testing Data Split
We split 890 for training set, 100 for testing set. We extract 20 samples from each classifier to make sure the testing set is balanced.  

## Upsampling classifier
Due to the imbalanced distribution of each persoanlity, we upsampled the 4 minority personality classes to '628'.



