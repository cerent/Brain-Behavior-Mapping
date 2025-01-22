# Brain-Behavior-Mapping

This Python script performs ridge regression to predict cognitive scores using functional connectivity (FC) data in 420 individuals from the Human Connectome Project. The regional FC was obtained as the sum of connections for each node (region) in the FC matrix, with diagonal values set to zero. FC matrix was obtained with the FreeSurfer 86 atlas (68 cortical and 18 subcortical/cerebellum). It uses nested cross-validation (5 fold cross validation) to tune the hyperparameter (alpha) and evaluates the model's performance by calculating the mean Spearman's correlation and explained variance. The script also visualizes the data and the results through heatmaps, scatter plots, and boxplots.

1. The first part of the code provide the data visualization such as the visualization of the fMRI time series, FC matrix, and node strength (regional FC).
  
2. The second part of the code provide the application of the ridge regression with nested cross-validation (5 fold cross validation) to tune the alpha parameter using the train dataset and to evaludate the model performance with the test dataset.

Please contact Ceren Tozlu cet2005@med.cornell.edu if you have any questions about the codes.
