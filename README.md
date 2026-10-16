# Predicting-Housing-Prices-and-calculating-error-using-Gradient-Descent
This is a Machine Learning model developed by Gradient Descent where mathematics such as calculus, statistics, and algebra are used to scale our variables, and  predict output ( in this example housing prices), we then simulate this many times to reduce error, and make our predictions closer to real-world data. 
Features & Implementation
	Phase 1: Preprocessing & Scaling
	Extracted feature and target vectors using pandas and numpy, as x and y the features are closes to change in our output which is price. 
	Applied Z-score normalization to ensure that our prices are within range and to reduce outliers in data so that error can also be reduced in the future. 
	Added bias/intercept column to feature matrix, and organized our data. 
	Phase 2: Mathematical Logic
	Hypothesis Function: Vectorized matrix multiplication (Xθ) for instant batch predictions. 
	Cost Function: Calculated Mean Squared Error (MSE) to quantify prediction error. 
	Phase 3: Gradient Descent & Optimization
	Iterative loop using calculus derivatives to step downhill and update weights. 
	Recorded cost history at each iteration to track convergence. 
	Visualized training curve with matplotlib showing steady error reduction. 
Results & Visualizations
	Final Intercept (θ_0): 180,913.39
	Final Feature Weight (θ_1): 56,273.19
	Final Cost (MSE): 156,992,1638.29

Tech Stack
	Language: Python
	Libraries: NumPy, Pandas, Matplotlib 
	Environment: Google Colab
