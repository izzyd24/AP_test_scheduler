# AP_test_scheduler
## Objective:
## Question: 
Given a unique, fixed start and end date, tasks with a specific alloted completion time, and 34 sources/CSVs, can we leverage a machine-learning model to automate/create a weekly schedule for a student (by month and course type)?

## Initial Thoughts: 
### Option 1: Manual Work
Gantt by setting start and end dates of each task, spanning from Sept. 1, 2023 to end date of April 1, 2023. 

### Option 2: ARIMA Model?

### Option 3: Optimization Libraries - Gurobi or CPLEX
#### General Steps: 
*** Assuming cleaned version of the 34 AP Test csv files...

1. Collect and prepare data: You will need to gather a dataset of tasks that have time constraints, along with their corresponding durations and deadlines. Ensure that the data is cleaned and formatted in a way that can be easily fed into the model.

2. Define the problem and select a model: Decide on a specific problem you want to solve, such as creating a weekly planner that maximizes task completion or minimizes schedule conflicts. Select an appropriate machine learning model based on the problem you have defined.

3. Train and evaluate the model: Use the prepared dataset to train the selected model. Evaluate the model's performance using appropriate metrics such as accuracy or F1 score.

4. Optimize and refine the model: Based on the evaluation results, iteratively fine-tune the model by adjusting hyperparameters and adding new features until you achieve the desired level of performance.

5. Deploy the model: Once the model is finalized, deploy it in an appropriate environment for use.
