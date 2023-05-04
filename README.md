# 9-class-PHEME
zubiaga 9 classes PHEME and remove mac ._ file

Dataset posted on 2018-06-10, 22:39 authored by Elena Kochkina, Maria Liakata, Arkaitz Zubiaga
This dataset contains a collection of Twitter rumours and non-rumours posted during breaking news.

The data is structured as follows. Each event has a directory, with two subfolders, rumours and non-rumours. 
These two folders have folders named with a tweet ID. 
The tweet itself can be found on the 'source-tweet' directory of the tweet in question, and the directory 'reactions' has the set of tweets responding to that source tweet. 
Also each folder contains ‘annotation.json’ which contains information about veracity of the rumour and ‘structure.json’, 
which contains information about structure of the conversation.

This dataset is an extension of the PHEME dataset of rumours and non-rumours (https://figshare.com/articles/PHEME_dataset_of_rumours_and_non-rumours/4010619), 
it contains rumours related to 9 events and each of the rumours is annotated with its veracity value, either True, False or Unverified.

This dataset was used in the paper 'All-in-one: Multi-task Learning for Rumour Verification'. For more details, please refer to the paper.

Code using this dataset can be found on github (https://github.com/kochkinaelena/Multitask4Veracity).

License: The annotations are provided under a CC-BY license, while Twitter retains the ownership and rights of the content of the tweets.

FUNDING
PHEME FP7 project (grant no. 611233)
HISTORY
2018-06-10 - First online date, Posted date
REFERENCES
https://figshare.com/articles/PHEME_dataset_of_rumours_and_non-rumours/4010619
