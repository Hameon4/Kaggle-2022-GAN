# Vanilla GAN-Based Training for Binary Classifier <br>
A kaggle contest that took time in the summer of 2022. This AI project's aim is to make a custom GAN-model to generate synthetic data and discriminate the two or for binary classification. Using the data provided in the kaggle challenge, conditions were to get an RMSE no more than 0.2 and a low RMSE delta (|pre GAN - post GAN|). The model proved to be consistent in providing RMSEs < 0.2 and the lowest RMSE delta recorded was 0.003.
<hr>
Intensive testing were implemented on this project, as different methods were tried to determine the best possible combination. Tabular and Pictorial were both tested, and tabular proved to be a better choice. For classification tests, all ensemble learning trees were tried, even supported vector machines (SVMs), and random forest tree had the best results, following xgboost. 
