# Week 1

1. **X and y:** `X` holds the features of each sample (e.g., petal length and width), and `y` holds the correct label (the flower species).
2. **train and test:** The model learns from the train data. The test data is kept aside, and the model has never seen it. I use it to check how well the model predicts.
3. **Why not test on train data:** The model has already seen that data, so it effectively memorizes it and scores very high. This doesn't show how it performs on new data, so I evaluate on the test set.
4. **random_state:** It fixes the random train/test split, so I get the same result every time I run the code.
5. **test_size experiment:** With less training data, the model learns less and accuracy drops (e.g., 0.77 with only 7 training samples).
