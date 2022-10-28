# Supportiv

On this project I tried to utilize all the common ways of approaching a NLP task. I didnt really take a look at scores. 

The following is the way I approached the project:

1- I cleaned the data and made the whole dataset 


  1-1: In the troll data, the subreddit is extracted and created a column with that name to later on mere with the text.
  
  1-2: Each Regular and Troll data assigned with a tag , 0 or 1 for classification.
  
  1-3: On troll data, "post", "link_title" and "subreddit" columns merge together simply to build the bigger text column.
  
  1-4: On Regular data, "post" and "subreddit" are merged the same way of troll.
  
  1-5: Replaced all urls with the word "url", using regex.
  
  1-6: Removed all the numbers, non alphabet chars, single letters, stop words, multiple spaces etc.
  
  1-7: Merged the data to form the final dataset
  
  
 2- Splitted data into train and validation for machine learning
 
 3- Created the vectorized form of text to be fed into Bi-directional LSTM.
 
 4- Creating the architecture of neural network.
 
 5- Compiling and fitting the model
