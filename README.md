# MSA_Project_2023Spring
This is the project detail in the course Multivariate Statistical Analysis taught by Jingyuan Liu in Xiamen University.

This project is a tentative answer to the kaggle competition [Benetech - Making Graphs Accessible](https://www.kaggle.com/competitions/benetech-making-graphs-accessible). The recognition and classification of statistical images in the competition are mainly completed. The overall solution is as follows: First, the original image data was converted into pixel data, and data augmentation was used to adjust the category imbalance problem. Then Principal Component Analysis(PCA) was used to reduce the dimension to 50 dimensions, and UMap was used to reduce the dimension to 10 dimensions. Finally, Decision Tree(DCT), Random Forest(RF), LightGBM, XGBoost and Support Vector Machine(SVM) were used for training and classification. The accuracy rate performance on the test set is about 90%.

In addition, this project also tried other schemes, including but not limited to: Convolutional Neural Networks(CNN), Resamling Methhod, t-sne dimensionality reduction, DenseMap dimensionality reduction, grid parameters searching, and Ensemble Learning, but ultimately did not make significant progress in accuracy.

All the code versions were completed by Python programming and stored in [kaggle platform](https://www.kaggle.com/code/yicheung1/cnn-method).
