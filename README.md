# Speech-Project

The project main subject is the US presidents speeches. 

The hypothesis:
  ● There is a unique characteristic to the speeches, based on who's the 
speaker or which party he belongs to.
  ● There is trends hidden in the speeches we can observe through out 
the yeas, only from a view from above in the data.


# About the data
Numeric information
  ● 600 speeches of 20 US presidnets
  ● Speeches from 1919 to 2021
  ● 43150 distinct different words (filtered from punctuations and stopwords). 

# Source and Obtaining
We scraped the website https://millercenter.org/the-presidency/presidentialspeeches ,downloaded from it 600 speeches.
Each speech saved as txt file with some relevant information at his topic like the name of the speaker and the date 
the speech was given. The data was prepared (removing stopwords and punctions), counted and ordered by date, appearances of word and so on.

# NLP - NLTK
We used NLP tools to view the data in a more indepth way to understand different trends that appear from the data. 
By tagging the data with NLTK we were able to find the Top 20 phrases in all the speeches. 
From that group, we checked the frequency of each phrase every year, in that way we can see different trends based on the use of the top phrases. 
We choose to present 6 phrase that has an interesting distribution.
Results- We can understand from the graph what were the ‘hot’ subjects of each year based on the phrase distribution. 
We can notice the change in the subjects of interest based on the phrases that the Presidents talk about in their speeches.
