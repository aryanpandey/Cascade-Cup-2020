# Round 2 Hackathon
As for our solution to this round, we implemented an XGBoost model on the dataset.

We tried log scaling of features, binning of features to give it a categorical appearance due to their better performance on tree based models, 
made quite a lot of new features and plotted the feature importance to see which features are the ones that affects the model most. 
There was a leak in the dataset in the ID column and including this column increased our score on the leaderboard.

We also tried implementing SMOTE to handle the class imbalance but for some reason, it didn't give us any better results.

Link to our implementation: [Round 2 Python Notebook](https://github.com/aryanpandey/Cascade-Cup-2020/blob/main/Round-2/Cascade-Cup-2020-Round2.ipynb)
