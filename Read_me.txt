Place your dataset CSV path or URL in DATASET_PATH and set LABEL_COL to the name of the target column
at the top of the script; optionally supply NUMERIC_COLS and CATEGORICAL_COLS 
(leave them empty to let the script infer types). Then run the script
 (for example python multi_conditional_wcgan_template or the corresponding template file): 
the script will train the model(s) generate synthetic samples to balance underrepresented classes
 and display a t-SNE plot comparing real vs. synthetic data (and other metrics).

