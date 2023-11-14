# polynomial-modeling-and-optimization
This repository contains Python code and a Jupyter Notebook implementing tasks related to polynomial modeling and optimization.
This repository contains Python code and a Jupyter Notebook implementing tasks related to polynomial modeling and optimization. The tasks are structured as follows:

**Task 1: Ideal Polynomial and Noisy Data Generation**
- Choose coefficients for a second-degree polynomial equation.
- Implement an evaluation function for any second-degree polynomial.
- Write a jittery evaluation function to simulate imperfect/noisy data.
- Generate 100 random x values in the [-10,10] interval using the jittery evaluation function.
- Plot the training data using matplotlib.

**Task 2: Initial Model and Visualization**
- Generate and store random coefficients for a second-degree polynomial as the initial model.
- Calculate the model's predicted y output values from the Task 1 training data x input values.
- Plot both observed values and predicted values on the same graph.
- Implement a mean squared error loss function.

**Task 3: Model Improvement**
- Decide on a learning rate and experiment if necessary.
- Implement a gradient calculation function for a second-degree polynomial.
- Check and adjust the model's coefficients to minimize the loss.
- Visualize the improvement by plotting training data, the original model, and the updated model.

**Task 4: Iterative Optimization**
- Iterate over evaluating current model loss, calculating gradients, adjusting model coefficients, and calculating new model loss.
- Implement a stopping condition for the iteration.
- Plot training data and predicted data, print final coefficients, and plot loss values over iterations.

**Task 5: Polynomial of Any Order**
- Implement tasks 1-4 for a polynomial of any order.
- Test the implementation on a 3rd order (cubic) polynomial.

The Jupyter Notebook provides detailed instructions, code, and visualizations for each task, allowing for a step-by-step understanding of polynomial modeling and optimization.
