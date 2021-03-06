# model_evaluation_for_HAR

This is the source code for "Model Evaluation Approaches for Human Activity Recognition from Time-Series Data" that was presented at AIME2021, June 17, 2021.  https://doi.org/10.1007/978-3-030-77211-6_23

The input to most of the files are X, y, sub(ject) numpy arrays that have been stored to a mapped filesystem.   These arrays are generated from the raw data by the code located in https://github.com/imics-lab/load_data_time_series

**MobiAct_data_explore.ipynb** was used to generate the values for the resampling and component versus total acceleration experiments.

**model_eval_HAR_stratification.ipynb** was used for the stratification experiments which (incorrectly) mixes subject data into the train and test sets.

**model_eval_HAR_defined_subject.ipynb** was used for the experimentation using subjects allocated to only one of train/test/validate.

**subject_split_generator.ipynb** was used to generate dictionaries containing subject splits that could be input into the load_data_time_series methods.

**Plots_for_model_eval.ipynb** was used to generate the plots that were not included in other files directly.

If you find this work useful please cite using this BibTeX
```text
@inproceedings{hinkle2021model,
  title={Model Evaluation Approaches for Human Activity Recognition from Time-Series Data},
  author={Hinkle, Lee B and Metsis, Vangelis},
  booktitle={International Conference on Artificial Intelligence in Medicine},
  pages={209--215},
  year={2021},
  organization={Springer}
}
```
