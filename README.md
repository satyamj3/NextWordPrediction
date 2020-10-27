# NextWordPrediction

This project is created and trained on Google Colab. So, you may find some paths of Google drive.
Following step I have followed while building this project.
  1. Preprocess text -> 
      * cleaning the raw text i.e. removing the unneccessary characters from the text
      * sent and word tokeknization
      * stop word removal
      * lemmatization
  2. Converting text tokens into vectors list using keras tokenizer
  3. Creating training data by forming sequence from the vectors list
  4. Model building
      * Creating sequential model with the size of total words
      * Added an Embedding layer with 1000 features/inputs
      * Added Dense layer with 1000 inputs
      * Added Dense(Output) layer with total input size of total words
      * Since it is a multiclass classification so Softmax activation function is used at the output layer.
  5. Model training is done on 250 epochs and has been saved as well for further use.
  6. Sample prediction is done using a few sentences.
  
