# AllenNLP Challengeset
The project is carried out in order to test the performance of Semantic Role Labeling for the course NLP Technology taught by Pia Sommerauer at VU Amsterdam. 

## Folder structure 
*`challenge_sets`
*`datasets`
*`results`

## Challenge_sets
The folder contains the notebooks used to create the challenge sets. In total there are 14 different notebooks but only 5 capabilities are being tested plus a fairness test. The notebooks are separated by the models that are used to create the semantic role labeling. 
The capabilities are as follows 
* Active and Passive
* Conjunction
* Denotation
* Gardenpath Sentence
* Transitive, Intransitive Verb 

For fairness a test on Western vs Non-Western names has been created. 

## Datasets
The folder contains the created challenge sets. They are created while running the notebooks. The files are stored as a txt file in a folder called 'datasets'. 

## Results
In results, the results of the CheckList on the datasets can be found. A fail rate indicates the performance of the Semantic Role Labeling. The files are stored as a csv file in a folder called 'results'. 
