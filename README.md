# Tag prediction for Stack Exchange Questions

Stack exchange is a popular message board that allows people to ask questions and give answers about a variety of subjects.   These questions are distributed across various boards such as 
- travel
- physics
- cooking
- scifi
Within each board, the questions have a short one sentence title, a longer body explaining the question in depth, and a list of "tags" that allow people to efficiently search for questions.  The tags are provided by the user.  

An example of this from the cooking dataframe would be 
* Title: How do I get chewy chocolate chip cookies?
* Content: My chocolate chip cookies are always too crisp.  How can I get chewy cookies, like those of Starbucks?   Thank you to everyone who answered, the biggest impact was to chill and rest the dough, however I also increased the brown sugar ratio and incrased a bit the butter.  Also adding maple syrup helped.  
* Tags: baking, cookies, texture

The goal of this notebook is to create a model which can predict the tags of a question on stack exchange.   Furthermore, I will want this model to not only work for one message board, but to be able to predict tags on message boards the model has not yet seen.   

## Running the notebook

To run the notebook, you will need python 2.7, along with the packages found in requirements.txt.  You will also need to get a stack exchange API key, which is freely available to use this.  In settings, change the line API_KEY='' to API_KEY='YOUR API KEY HERE'  You will also need to get a stack exchange API key, which is freely available to use this.  In settings, change the line API_KEY='' to API_KEY='YOUR API KEY HERE'.
