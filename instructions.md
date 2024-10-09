To test your validation dataset, kindly do the following:

Go to the end of the file where SHAP Interpretation ends. 
Uncomment the code to make it active, don't uncomment the comments off course. 
Begin this from this code snippet:

# Load the pretrained pipelines and models
#preprocessor = joblib.load('preprocessing_pipeline.pkl')
#feature_interaction_pipeline = joblib.load('feature_interaction_pipeline.pkl')
#pca = joblib.load('pca_model.pkl')
#stacking_clf = joblib.load('trained_stacking_clf.pkl')

Make it functional by removing the hastags from the code. 

You need to make changes only in 2 code snippets to test out the model. 

# Validation data
#X_valid = np.random.rand(200, 21)  # Replace with actual validation data

.
.
. 

# Evaluate predictions
#y_valid = ...  # Replace with actual labels


Then you're all set to test your data!
