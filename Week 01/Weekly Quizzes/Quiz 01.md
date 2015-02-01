Quiz
====

Question 1
----------

A computer program is said to learn from experience E with respect to some task T and some performance measure P if its performance on T, as measured by P, improves with experience E. Suppose we feed a learning algorithm a lot of historical weather data, and have it learn to predict weather. In this setting, what is E?

### Answer

The process of the algorithm examining a large amount of historical weather data.

### Explanation

T := The weather prediction task.  
P := The probability of it correctly predicting a future date's weather.  
E := The process of the algorithm examining a large amount of historical weather data.  

Question 2
----------

Suppose you are working on weather prediction, and you would like to predict whether or not it will be raining at 5pm tomorrow. You want to use a learning algorithm for this. Would you treat this as a classification or a regression problem?

### Answer

Classification

### Explanation

Classification is appropriate when we are trying to predict one of a small number of discrete-valued outputs, such as whether it will rain (which we might designate as class 0), or not (say class 1).

Question 3
----------

Suppose you are working on stock market prediction, and you would like to predict the price of a particular stock tomorrow (measured in dollars). You want to use a learning algorithm for this. Would you treat this as a classification or a regression problem?

### Answer

Regression

### Explanation

Regression is appropriate when we are trying to predict a continuous-valued output, since as the price of a stock (similar to the housing prices example in the lectures).

Question 4
----------

Some of the problems below are best addressed using a supervised learning algorithm, and the others with an unsupervised learning algorithm. Which of the following would you apply supervised learning to? (Select all that apply.) In each case, assume some appropriate dataset is available for your algorithm to learn from.

### Explanation

1) Take a collection of 1000 essays written on the US Economy, and find a way to automatically group these essays into a small number of groups of essays that are somehow "similar" or "related". :=  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This is an unsupervised learning/clustering problem (similar to the Google News example in the lectures).  

2) Given a large dataset of medical records from patients suffering from heart disease, try to learn whether there might be different clusters of such patients for which we might tailor separate treatements. :=  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This can be addressed using an unsupervised learning, clustering, algorithm, in which we group patients into different clusters.  

3) Given genetic (DNA) data from a person, predict the odds of him/her developing diabetes over the next 10 years. :=  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This can be addressed as a supervised learning, classification, problem, where we can learn from a labeled dataset comprising different people's genetic data, and labels telling us if they had developed diabetes.  

4) Given 50 articles written by male authors, and 50 articles written by female authors, learn to predict the gender of a new manuscript's author (when the identity of this author is unknown). :=  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This can be addressed as a supervised learning, classification, problem, where we learn from the labeled data to predict gender.  

5) In farming, given data on crop yields over the last 50 years, learn to predict next year's crop yields. :=  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This can be addresses as a supervised learning problem, where we learn from historical data (labeled with historical crop yields) to predict future crop yields.  

6) Examine a large collection of emails that are known to be spam email, to discover if there are sub-types of spam mail. :=  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This can addressed using a clustering (unsupervised learning) algorithm, to cluster spam mail into sub-types.  

7) Examine a web page, and classify whether the content on the web page should be considered "child friendly" (e.g., non-pornographic, etc.) or "adult." :=  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This can be addressed as a supervised learning, classification, problem, where we can learn from a dataset of web pages that have been labeled as "child friendly" or "adult."  

8) Examine the statistics of two football teams, and predicting which team will win tomorrow's match (given historical data of teams' wins/losses to learn from). :=  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This can be addressed using supervised learning, in which we learn from historical records to make win/loss predictions.  

Question 5
----------

Which of these is a reasonable definition of machine learning?

### Answer

Machine learning is the field of study that gives computers the ability to learn without being explicitly programmed.

### Explanation

This was the definition given by Arthur Samuel (who had written the famous checkers playing, learning program).
