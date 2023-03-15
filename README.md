# Audit-DataSet
Used Rattle to find the best SVM model to predict the cost of carrying out a tax audit on a list of business. Used area under the ROC curve (AUC) as my evaluation criterion and used the model to build a profit curve


![Screenshot (59)](https://user-images.githubusercontent.com/114897374/225192965-5ce3d426-1de3-440a-ab0e-d6ac09d1961f.png)


The largest Area Under the ROC Curve is 0.8275 using the Kernel RBF with a penalty parameter of 10.
-	Rebuilding using the Kernel RBF with a penalty parameter of 10 and the data partitioned to 80/0/15

ROC Plot

![Picture7](https://user-images.githubusercontent.com/114897374/225193075-5c4deb52-efad-4ca8-ae49-437cb0823daf.png)

An AUC (Area Under the Curve) of 0.85 on a ROC plot indicates that the classifier has a good level of discrimination between the positive and negative classes. The ROC curve will show a curve that is relatively steep and reaches close to the top left corner of the plot.

Profit Curve

![Picture8](https://user-images.githubusercontent.com/114897374/225193326-c807f2bd-302a-447b-a059-2ee9d6f46016.png)

Based on the result of the Profit curve, of the 300 tax returns, only 56 or 18.4% should be audited
