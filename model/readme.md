- **figure.py** : Plot ROC and PR curves of the SVM,RF and MLP model.
- **metrics.py**: Compute the predicted performance indicators.
- **mlp.py**: The MLP model code , which can compute the performance of the dataset , also can be used select the optimal parameter for MLP.
- **score.py**: Use the MLP model to compute the predicted scores of all lncRNAs.
- **rf.py**: The RF model code.
- **shuffle_mlp.py**: The MLP model was used for Shuffle experiment. The dataset was fixed, and the positive and negative labels were shuffled 1000 times. Each performance was calculated separately.
- **shuffle_rf.py**: The RF model was used for Shuffle experiment. The dataset was fixed, and the positive and negative labels were shuffled 1000 times. Each performance was calculated separately.
- **svm.py**: The SVM model, which is used for computing the performance of human and mouse dataset , and doing shuffle experiment 1000 times as described above.
- **svm_module.py** : The SVM model code.