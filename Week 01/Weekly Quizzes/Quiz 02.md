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
![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0208.png "Mask")  
Consider the linear regression model ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0201.png "Mask"). What are the values of ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0202.png "Mask") and ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0203.png "Mask") that you would expect to obtain upon running gradient descent on this model? (Linear regression will be able to fit this data perfectly.)  

### Answer  
![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0204.png "Mask")  

### Explanation  
![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0205.png "Mask")  

Question 03
-----------  
![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0206.png "Mask")  

### Answer  
3  

### Explanation  
![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0207.png "Mask")  

Question 04
-----------  
Let f be some function so that f(![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0202.png "Mask"),![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0203.png "Mask")) outputs a number. For this problem, f is some arbitrary/unknown smooth function (not necessarily the cost function of linear regression, so f may have local optima). Suppose we use gradient descent to try to minimize f(![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0202.png "Mask"),![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0203.png "Mask")) as a function of ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0202.png "Mask") and ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0203.png "Mask"). Which of the following statements are true? (Check all that apply.)  

### Explanation  
![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0209.png "Mask")  

Question 05
-----------  
Suppose that for some linear regression problem (say, predicting housing prices as in the lecture), we have some training set, and for our training set we managed to find some ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0202.png "Mask"), ![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0203.png "Mask") such that J(![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0202.png "Mask"),![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0203.png "Mask"))=0. Which of the statements below must then be true? (Check all that apply.)  

### Explanation  
![alt text](https://github.com/UtkarshPathrabe/Machine-Learning-Stanford-University-Coursera/blob/master/Week%2001/Weekly%20Quizzes/Quiz0210.png "Mask")