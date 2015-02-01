Quiz 02
=======  

Question 01
-----------  
Consider the problem of predicting how well a student does in her second year of college/university, given how well they did in their first year. Specifically, let x be equal to the number of "A" grades (including A-. A and A+ grades) that a student receives in their first year of college (freshmen year). We would like to predict the value of y, which we define as the number of "A" grades they get in their second year (sophomore year).  

Questions 1 through 4 will use the following training set of a small sample of different students' performances. Here each row is one training example. Recall that in linear regression, our hypothesis is ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0201.png "Mask"), and we use m to denote the number of training examples.  

| x | y |
|:-:|:-:|
| 3 | 2 |
| 1 | 2 |
| 0 | 1 |
| 4 | 3 |  

For the training set given above, what is the value of m? In the box below, please enter your answer (which should be a number between 0 and 10).  

### Answer  
4  

### Explanation  
m is the number of training examples. In this example, we have m=4 examples.  

Question 02
-----------  
Consider the following training set of m=4 training examples:  
| x | y |
|:-:|:-:|
| 1 |0.5|
| 2 | 1 |
| 4 | 2 |
| 0 | 0 |  
Consider the linear regression model ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0201.png "Mask"). What are the values of ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0202.png "Mask") and ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0203.png "Mask") that you would expect to obtain upon running gradient descent on this model? (Linear regression will be able to fit this data perfectly.)  

### Answer  
![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0204.png "Mask")  

### Explanation  
![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0205.png "Mask")