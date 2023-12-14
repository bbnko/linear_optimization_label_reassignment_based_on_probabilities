<h1> Linear Optimization - Label Reassignment based on predicted probabilities <h1>


<h3>  
Provided dataset contains simulated records of users' self-reported pet ownership labels and their purchasing activity.
  
Some users seem to behave differently from what their label says, thus we suspect that their self-reported label is incorrect. Incorrect labels create inconsistencies between behavior and assignment and thus need to be corrected.

At the same time, we would like to preserve the composition of our user set, ensuring that the proportions of 0/1 labels remains the same.
<h3>  




<h1>  
IPython notebook contains the following steps:
<h1>  
<h3>  
  - Data preparation
<h3> 
<h3>   
  - Training the model, assessing results vs. random assignment, predicting ownership probability based on purchase behavior
<h3> 
<h3>   
  - Defining a solver, cost function and constraints
<h3> 
<h3>   
  - Running the solver, performing label reassignment
<h3> 
<h3>   
  - Visualizing the results
<h3> 
