# Classification-of-Psychological-States-Using-Non-EEG-Signals
This is a group project.
The project discusses classification of four different psychological states related to stress using non-neurological (non-EEG) signals. 
The data analysis process includes data pre-processing,data cleaning and dimensionality reduction using PCA along with other data manipulation techniques. 
The next step includes developing several classification models as KNN, multi-layer perceptron, and random forest. The purpose of developing several models is to be able to carry out comparisons using the accuracy metriic and provide accurate insights.
For each model, two types of validation techniques were used for the training and testing phases.The first is the default cross validation wherer 80% of the data were used to train the model and 20% were used for testing.
The second is leave-one subject out validation where all the remaining subjects were used for training while the last subject is used for testing and the process was iterative.
More details are included in the report.
