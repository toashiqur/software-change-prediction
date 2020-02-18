# Software Change Prediction
Change in software is almost inevitable due to various issues such as error, bug, security flaw etc. Prediction of change prone files can help the developers to be more focused on the files that may require change. Besides, it can help software project managers to make better decisions regarding software development and maintenance. 

Selection of language features, and their combinations can have a significant effect on the quality of the developed code. Poorly selected features can degrade the code quality, and accelerate the need of change. In this project, we explore whether a file’s language feature use can be used together with deep neural network to predict the file’s change proneness. 

We encode feature usage profile of source files using feature appearance and density vectors, and use these profiles to train deep neural network (DNN) for predicting the source files may require change. Besides, we find which vector, among feature appearance vector, density vector, and their combination, is the most useful vector, and whether feature data needs to be
normalized.

Experiments are performed using two open source php software phpbb and WordPress. The results are evaluated against four other machine learning classifiers K-NN Classifier, Support Vector Classifier, Decision Tree Classifier, and Gaussian Naive Bayes Classifier. Results show the DNN model trained with feature use profile can successfully predict change proneness of source files. The ROC-AUC of the developed DNN is 89.53%. It achieves F-measure 93.27% and accuracy 88.26%. No other model was successful to achieve that performance. The findings of this project clearly shows language feature can be used for training deep neural network and predicting issues related to source code.

Technology Used:
* Python
* Tensorflow
* Scikit-learn
* Pandas
* Numpy
* Matplotlib
* Deep neural network
* Support Vector Classifier
* Decision Tree
* K-nearest Neighbors
* Naive Bayes
* Jupyter Notebook

The report is available for download from [Software Change Prediction][report-link]
<script src="https://gist.github.com/toashiqur/e5aee01a310e037eb620baaeecd988b5.js"></script>

[report-link]:https://gist.github.com/toashiqur/e5aee01a310e037eb620baaeecd988b5.js
