For this project, I used the Red Wine Quality dataset (data link: https://archive.ics.uci.edu/dataset/186/wine+quality) to build different classification models to predict whether a particular red wine is of “good quality” " or not.

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: http://www.vinhoverde.pt/en/ or the reference [Cortez et al., 2009].  Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks.  The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.



The main tasks of this project are: 
  
  1, Reduce the data dimensionality to 2 dimensions using PCA and display the data after dimensionality reduction, visualize the data and also normalize the data
  
  2, Apply linear regression, with rounding the model output, train the model with training data and then try to predict on test data. Check the model’s suitability through the accuracy (loss) index.
  
  3, Put the original problem into data classification form. With the following ideas:
  
    a) Use classification models: logistic regression, Naïve Bayes matching; to perform this classification problem. Compare
    methods on the following criteria: Accuracy, precision, recall and running time.
    
    b) Reduce the number of dimensions to half (round up) the current number using PCA. Then again use two stool models the above mentioned type to resolve. Compare the            original data case and the reduced data case. Note the need to reduce dimension on synthetic data including training and testing.
    
    c) Use the appropriate Support Vector Machine method to solve the classification problem on reduced data in point b. Compare with the methods in idea b on the same           criteria.
  
