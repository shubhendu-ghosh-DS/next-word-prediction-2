# next-word-prediction-2
![AI-Feature-Image-640x353](https://user-images.githubusercontent.com/77840111/183000558-a6f01fed-9efd-43bd-ac72-5d7f6a94c28b.jpg)

## Data  
In this project we are using the book The Picture of Dorian Gray by Oscar Wilde as a dataset.  
## Methodology  
1. first we will have a text corpus as a dataset.  
2. we will do NLP preprocessing for text data and create a vocabulary of tokenized words  
3. we will take first 4 words of va sequence as an input ( independent variables ) and the 5th word as output ( depenedent variable)  
4. then we will train a neural network (LSTM) on the data  
5. finally we will predict our model with random sequences  

## Requirements
- tensorflow
- numpy
- pickle
- os
