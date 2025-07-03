# ML.ai-Hackathon

1. The first step is EDA --> 1.1 Load the dataset --> 1.2 Explore the data using describe --> 1.3 Treating Missing Values--> 1.4 Outlier Analysis
2. Building Supervised Learning Model for labeled_df(Now don't change goals untill doing the below thing)
 --> First we will apply logistic regression, which will take 75% samples from each class of labeled_df. Use vectorized approach.
 --> We will then Use L2 regularization. Visually plot the weights corresponding to each features so as to knwo how each features is important. Features whose weight's magnitude is very very less drop them, those features are not useful in detection of cancer. There are some gene features only which are useful for cancer detection. Now, store these important features.
 --> Now use PCA on those important features. This increases the model performance. Now visually plot how each PCA contribute. Drop those PCA's whose contribution in capturing the variance of data is very very less. The remaining important PCA's are your now new modified features.
 --> Use Logistic regression for these new modified features. Use 75% samples from each class
 --> Now, GridSeachCV, class weights = "Balanced" , cross validation. etc. which are useful in tuning the hyperparameters and more things have a look at them also.

   







* In outlier analysis, I replace the outliers by the class wise mean. Still there exist some outliers. For them I replace them by the upper bound. I don't knwo how which of both is better and when
Checkpoint 1--> before day 4 end do EDA of unsupervised and complete supervise model
