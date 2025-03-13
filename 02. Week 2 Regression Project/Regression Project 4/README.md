# Kaggle competition guide for Machine Learning students

## Watch the video or go through notebooks
- You can either read this document and go through the notebook files i.e. `buildmodel.ipynb` then `modelpredict.ipynb`
- Or, you can watch this [YouTube Video](https://youtu.be/-wASK_i82n0)
- Whichever works for you so that you are not stuck working on your first Kaggle project

## Folder Structure
In this folder, we have the following files/folders:
1. `data` Folder containing the data downloaded from kaggle i.e. `train.csv` `test.csv` and `sample-submission.csv`
2. `final` Folder containing exports from my code i.e. `model.sav` and `submission.csv`
3. `buildmodel.ipynb` Notebook file where we build the model using the training data
4. `modelpredict.ipynb` Notebook file where we generate the final submission from testing data

## Summary of the steps to take

### Phase I: Build the Model with `train.csv`
1. Import, explore, and visualise your data
2. Preprocessing and/or prepare your data for model
3. Train, find the optimal model, and export/save the final model

### Phase II: Make predictions on `test.csv`
1. Run the same preprocessing stesp you ran on your training data
2. Make predictions using the model you trained and saved previosuly
3. Export the submission file (Use `sample-submission.csv` as your template)
