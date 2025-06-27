Brief Overview:

Downloaded a dataset from kaggle
mapped char to int 
Split the dataset into train and val (so that some data is available for training and sthe rest for validation)
set target as :
  if i th character is considered then the 'i+1'th character is target.
used bigram language model-(tokenization)
  Splits text into tokens (chunk of characters).
  Counts how often each word follows another.
  uses a softmax for frequency analysis.
  given a token, what is probability of a particular token to come next.
  repeating this over creates a sequence.

To make the model understand sentences, made multi head attention model 
  -multiple parallel relations to detect the sentence

FeedForward network to store informstion of each token independently 



Videos I watched:

  [week1](https://www.youtube.com/watch?v=kqtD5dpn9C8)
  [week 1](https://www.youtube.com/watch?v=QUT1VHiLmmI)
  [week 1](https://www.youtube.com/watch?v=vmEHCJofslg)
  [week 1](https://www.youtube.com/watch?v=DAQNHzOcO5A)

  vdo 74 to 84
  [week 2,3](https://www.youtube.com/watch?v=Gv9_4yMHFhI&list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF)

  vdo 86 to 91
  [week 4](https://www.youtube.com/watch?v=Gv9_4yMHFhI&list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF)
  
  [week 5](https://www.youtube.com/watch?v=OIenNRt2bjg)
  
  [week 6](https://www.youtube.com/watch?v=kCc8FmEb1nY)
  
  
  
  
  
