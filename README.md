# Question Classifier
### A classifier to predict the type of answer a question expects. 
---
### Content

- Question Answering system and need for Question Classifier
- Data Sources
- Comparing the various approaches
- Implementing the project

## Question Answering system and need for Question Classifier
In today’s world we rely on technology to find the answer to everything even with basic to no knowledge of coding. This is achieved through Question Answering Systems, which translates user query, often quoted in natural language, into a structured query which can be used to extract relevant information and thus answer the question.
Question Answering systems analyse the question for its defining features, retrieve information based on it and then extract the final answer. In this sequence of steps, the most crucial is the question analysis, as that entails extraction of the textual features from the user input and tailoring the answer predication is completely based on it. Question analysis involves of pre-processing the text(noise removal, lexicon normalization) and extracting defining features such as the subject, type of answer expected etc.
Question Classifier helps identify the type of answer demanded by a question, for instance a *when* question will expect a time or date as answer while a *where* question will expect a location as the answer.

## Data Sources
The data used is "Experimental Data for Question Classification" by Xin Li and Dan Roth. It can also be found [here](https://cogcomp.seas.upenn.edu/Data/QA/QC/)

## Comparing the various approaches
I have used TensorFlow's Keras library to explore various text classifications techniques such as DNN, CNN, RNN, LSTM and GRU.

## Implementing the project
To implement the project, download the dataset present in the 'Data' folder and open the .ipynb file for the implementation you want to see. The file can be opened in jupyter notebooks. Just select the run all cells option to execute the file. It might take a while to train some of the models.
The last cells have some custom statements added to check the prediction on data outside of the test - train sets. You can change the statements or add more to see the model in action.
