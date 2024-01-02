# A Couple of Things to Point Out
## What is Machine Learning?
- Study that gives computers the ability to learn without being explicitly programmed. (Artuel Sammuel)
- Two main types: Supervised; used most in real world applications, rapid advancement(course 1 and 2) and Unsupervised (course 3), recommender systems and reinforcement learning

## Supervised Learning part 1
Supervised Learning: learn from data labeled with the right answer
Concept: Learn X to Y or input to output mappings 
Find appropriate curve/line to fit with your new data
Regression Example: learn to predict house price
Regression Concepts: Predict all of the infinitely many number of possible numbers

## Supervised Learning Part 2
- Classification Example: Breast Cancer Detection using a patients medical records
- Clasification Concept: the output is only two possible outputs/categories, it could be 3 possible categories or more. So to summarize, classification predict categories. Categories could be numeric or non-numeric output. It could be 0, 1 or 2. 
- Character of Classification: two or more inputs.

## Unsupervised Learning Part 1
- Unsupervised learning/Clustering Algorithm: Find Something interesting in unlabeled data, we’re not trying to supervise th algorithm, the data can be assigned to 2 difference groups or two difference clusters
- Which is a type of unsupervised learning algorithm, takes data without labels and tries to automatically group them into clusters

## Unsupervised Learning Part 2
- Data only games with input x but NOT output labels Y
- Algorithms has to find structure in the data
- Clustering: group similar data, points together
- For instance: anomaly detection: find unusual data points
- Dimensionality reduction: compress data using fewer numbers

## Jupyter Notebook
- Markdown cells
- Code Cell (shift enter to Run)

## Linear Regression Model Part 1
- For Instance: House sizes and prices
- Training a model by giving data that was a right answer
- Terminology: x for input features, y refers to output or target variable, m refers to number of training example or rows in the table, (X,Y) single training example, 

## Linear Regression Model Part 2
- 1) Training set (input features, target variables)
- 2) learning algorithm will produce function
- 3) Function (f) : model that features makes a prediction (y-hat)
- In this algorithms, size house of ur clients will predict with ur model to know clients prices  
- How to represent (f)? f(x) = wx + b
- Y-hat refers to the estimate of prediction for the output variable y
- Y refers to output variable or target

## Cost Function Formula
- W, b is paramater to get better model and CAN BE ADJUSTED. It called as weight or coefficients as well
- f(x) = wx + b
- f(x) similar to y-hat
- How to Find Values of W,B in order to get the tru target y-hat for many or all training example ?user cost function or Squared error cost function for linear regression problem 

## Cost Function Intuition
- 1. Model: fw,b(x) = wx + b
- 2. Parameters: w,b
- 3. Cost Function (J): to find value of w, b which fit with ur actual true data
- 4. Goal: minimize J(w,b)
- How to choose parameter w in order the model fit the data relatively well? When the cost J is at or near a minimum. When the cost is relatively small, closer to zero, it means the model fits the data better compared to other choices for w and b.
- To summarize: f and J has a corelation 

## Visualizing The Cost Function
- 3D Surface Plot of Cost Function is like soup bowl

## Visualization Examples
- Counter plot terms refers to visualization 
Notes: Best model Characteristics: Minimize cost function J to get fit line. 

## Implementing Gradient Descent
- Gradient descent is an algorithm for finding values of parameters w and b that minimize the cost function J
- Alpha  also called the learning rate. Alpha is to controls  how big a step you take downhill.
- Characteristics: repeat until convergence; means reach the point at a local minimum whether parameter b and w no longer change much with each additional step that you take
- Simultaneously update w and b: update old w and b to new w and b
- This updates the parameter by a small amount, in order to reduce the cost J

## Gradient Descent Intuition
- Learning rate and derivative results will update to parameter w and b
- Learning rate is always positive number
- If derivative number is positive(>0), values of w will be closer to 0 or decreasing
- If derivative number is negative(<0), values of w will be increase and go to minimum J

## Learning Rate (Alpha Notation)
- If the learning rate is too small, then gradient decent will work but it will be SLOW 
- If the learning rate too large, the creating the sens may OVERSHOOT and may never reach the minimun, may fail to converge or DIVERGE
Conclusion: Near a local minimun, gradient decens will automatically take smaller steps thats because as we approach the local minimum, THE DERIVATIVE AUTOMATICALLY GETS SMALLER , also updates steps become smaller,
NOTES: Can Reach Mininmun Without Decreasing Learning Rate or Alpha 

## Gradient Descent for Linear Regression
- Convex function is of bowl shaped function (global minimum not a local minimum) and it is only single local minimum
  
## Running Gradient Descent 
- Take a steps to get a global minimum, get straigt fit line
- “Batch” gradient descents: each step of gradient descent uses all the training examples


