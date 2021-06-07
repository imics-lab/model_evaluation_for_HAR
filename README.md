# model_evaluation_for_HAR

This is the source code for "Model Evaluation Approaches for Human Activity Recognition from Time-Series Data" that will be presented at AIME2021.

The input to most of the files are X, y, sub(ject) numpy arrays that have been stored to a mapped filesystem.   These arrays are generated from the raw data by the code located in https://github.com/imics-lab/load_data_time_series

**MobiAct_data_explore.ipynb** was used to generate the values for the resampling and component versus total acceleration experiments.

**model_eval_HAR_stratification.ipynb** was used for the stratification experiments which incorrectly mix subject data into the train and test sets.

**model_eval_HAR_defined_subject.ipynb** was used for the experimentation using subjects allocated to only one of train/test/validate.

**subject_split_generator.ipynb** was used to generate dictionaries containing subject splits that could be input into the load_data_time_series methods.

**Plots_for_model_eval.ipynb** was used to generate the plots which were not included in other files directly.
