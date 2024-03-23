# Deep-Learning-Challenge

## Preprocess the data
  * Using Google Colab
  * Dependencies
      * sklearn.model_selection import train_test_split
      * sklearn.preprocessing import StandardScaler
      * pandas
      * tensorflow 
      * matplotlib.pyplot 
      * numpy 
   * Import the data; visualize the import and clean the data, eliminating any unecessary columns and renaming columns, etc as needed. Made a copy of the dataset for manipulations.
   * Get the unique number of values in each column, bin them and selected cutoff points (<500) for application type and (<1000) for classification.
   * Converted the categorical data to dummy variables using yes = 1, no = 0.
   * Split the data into the train/test environment, scale it, transform and fit the model.

## Compile, Train and Evaluate the Model
  * Define the model by using the length of the X trained, scaled data for input features and using 3 layers and an output layer.
  * Ran the model several times, was unable to achieve above 72%. Manipulations were performed in the bins, layers, epochs, and activations. 
