# report

# Set 4 hours for this task and ran out of time, but put together this doc and the "main" file
# The majority of notes are in the main file and discuss the data proccessing, classification model selection and the nlp task
# Had an issue installing the model I needed for the nlp task so I used a differnt model just to show how it would be done

# Used a random forest classifier for the model 
# notes have been added to the code (jupyter notebook)

# key results: 75% accuracy for classifying whether a patient will be readmitted
# Roc-auc was only 0.5 so no better than flipping a coin -> needs to be improved before being used practiacally, 
# using more data or fine tuning hyperparameters 
# using gridsearch + utilising discharge notes
# More data should improve evaluation metrics, 200 records didn't result in good evaluation metrics
# With more time, you could try other models, i.e., logistic regression or neural net