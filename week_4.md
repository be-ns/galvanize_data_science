### Week 3 of the Data Science Immersive:  
#### Supervised Learning
Much coffee was involved in the making of this week. 
![morning routine](https://media4.giphy.com/media/3jVT4U5bilspG/giphy.gif)

##### Brief forward  
  * This week was both the most challenging and the most rewarding. (I may be starting every post that way from here on out). 
  We got into real, complicated, useful algorithms. We struggled through 
  coding them ourselves then learned how to do it efficiently with libraries. The difficulty of topics like Gradient Descent was enough to make 
  even math majors slightly woozy, because calculating it from scratch takes a minute or two. Random Forests were also stressful 
  since we used OOP with three meta classes to get through the different stages of the forest, tree, and nodes (more on that below). 
  Basically each day of this week we learned a subject, tried to code it by hand to understand it, then used the built in libraries in the 
  afternoon to make sure we were on track with it. For all of the exercises, pair programming was incredibly beneficial because we could 
  leverage the knowledge of one another (some are better at math, others at programming), and work to tune hyperparameters (attributes of the model itself).
  
  We also had guest speakers during lunch almost every day. Among them: The Denver Nuggets spoke about analytics in professional basketball. 
  A startup spoke about using data science to optimize watering for crops in big farming. It was awesome to hear how the problems and skills 
  we are working on are so useful to everything from predicting Free Agent success to increasing yield while decreasing water usage. 
  So freaking cool. 
  
     
#### Topics Covered:

1. __Gradient Descent__ 
  ![Following the curve of a signal to a minimum](https://media3.giphy.com/media/xQtCQI990TOs8/giphy.gif)
  * This was one of the best parts of the week. It was fascinating. And I had a brilliant partner for pair programming that 
  helped me to conceptually understand all the nuance of how to code it because he knew how to do the math by hand if needed.
  Here's the high-level overview:  
   * You can calculate the 'slope' of a line that isn't straight and work your way towards the minimum or maximum of the section. 
  It's super useful, because you could find the 'slope' of the error rate and follow it down to the minimum to get the lowest error 
  rate. There are libraries to help it run, and it works under the hood in Neural networks and logit functions, so this is 
  mostly for being able to debug and understand what's going on under the hood. The details are (most of the time) abstracted away. 
 
  
2. __Decision Trees / Bagging / Random Forests__  
 ![Growing branches](https://media2.giphy.com/media/98a5UJBwhnrz2/giphy.gif)  
 * These are some of the more interpretable, flexible models you can use. At a high level it's a lot of `if` splits on data based on 
 calculating information gain from the possible range of splits. Think about it like this - if you had a big bag of apples and 
 wanted to have all the green apples in one bin and red apples in another you'd just look through the apples and say 'if it's red put in this basket, otherwise put 
 in the other one. Random Forests make a ton of trees and average the result to a pretty high accuracy. 
 
3. __SVMs__
* Imagine a billiards table with striped and solid balls spread out. If they are intermixed, you can't quite separate the two types of balls 
linearly. A SVM is a type of algorithm that projects the features into multidimensional space to allow us to do just that. 
It is both complext to understand mathmetically and simple to understand conceptually, which makes it a very fun algorithm to work with.
![SVM Classifier](https://media1.giphy.com/media/D4BV18qywdzj2/giphy.gif)

4. __Case Study__
* All day Friday was devoted to a case study where we were given about half a million rows of data with 53 feature columns. We were divided into 
teams and worked from Git all day trying to recreate a Kelly Blue Book type price predictor for Tractors and Heavy machinery. It was crazy fun. My algorithm ( a Random Forest Regressor with 9 feature columns that utilized a 'cabin quality' feature I engineered) 
got second place in the class. How's that for 'Oh so you don't have a math background?'

Coming out of this week I'm feeling incredibly excited about where we are headed. I showed my smartest friend from college some of the stuff we were working on and he admitted he couldn't understand the math behind it. I can feel my inner nerd coming out hardcore, and it feels great. 
 
