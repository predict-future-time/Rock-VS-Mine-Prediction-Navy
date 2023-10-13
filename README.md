# Rock-VS-Mine-Prediction-Navy
Distinguishing Rocks from Naval Mines using Sonar Data.
In this project, we have undertaken the task of developing a predictive model to classify underwater objects as either rocks or naval mines using sonar data. Leveraging a dataset sourced from Kaggle, our primary objective is to create a robust model capable of effectively distinguishing between these two classes. The project holds significant implications for applications in underwater security and environmental monitoring, where accurate object classification is paramount.

Key Project Operations:

Data Collection: The dataset was collected from Kaggle, offering a wealth of information on underwater objects. It encompasses 208 observations, each equipped with 61 attributes. Within this dataset, we identified 60 numerical independent variables and a solitary categorical target variable.

Data Processing: During the data processing phase, the dataset was diligently reviewed for null and duplicate values, ensuring the quality of the dataset. Features were carefully selected, and the target variable was identified. The dataset was subsequently divided into the feature matrix (X) and the target matrix (Y). We created training and test datasets, reserving 20% for testing.

Model Selection: After thorough analysis, Logistic Regression was selected as the most suitable model for this classification task. Its simplicity, efficiency, and suitability for binary classification align perfectly with our objective.

Model Training: The Logistic Regression model underwent rigorous training on the training dataset. This training allowed the model to grasp the underlying patterns in the data, ultimately minimizing the log loss function.

Model Evaluation: We evaluated the model using a range of essential metrics, including accuracy, precision, recall, and the F1-score. These metrics offer a comprehensive view of the model's ability to make accurate predictions and identify mines effectively.

Building a Prediction System: Our trained Logistic Regression model now serves as a dependable predictive system. When provided with sonar data as input, this system can reliably classify underwater objects as rocks or mines.

Conclusion: 

Matrices: Precision (Positive Predictive Value): Precision is at a reasonable level of 75%, indicating that the model is fairly accurate when it predicts "Mine."
          Recall (Sensitivity): The recall score of 81.8% suggests that the model captures approximately 81.8% of actual "Mine" instances, demonstrating its 
          ability to correctly detect these instances.
          F1-Score: The F1-Score, at 78.3%, indicates a good balance between precision and recall, providing a comprehensive assessment of model performance.

Accuracy Scores: The test data accuracy of 76.1% indicates that the model correctly predicts 76.1% of all instances in the test dataset.
                 The training data accuracy of 83.4% demonstrates that the model is able to correctly classify 83.4% of the training dataset.

Confusion Matrix: 9 Observations of Rock were actually classfied as Rock.
                  2 Observations of Rock were incorrectly classified as Mine.
                  3 Observations of Mine were incorrectly classified as Rock.
                  7 Observations of Mine were correctly classified as Mine.

Overall Assessment: The model's accuracy scores for both the test and training datasets are reasonably high, indicating a good overall performance.
                    The precision score suggests that the model is fairly accurate when identifying "Mine."
                    The recall score, at 81.8%, demonstrates the model's ability to detect a significant portion of "Mine" instances.
                    The F1-Score balances precision and recall, providing a comprehensive view of model performance.

Recommendation:
The model is performing well, with high accuracy, balanced precision, and recall. Depending on the specific requirements, we can fine-tune the model to optimize precision, recall, or the F1-Score to align with the goals of your application. In conclusion, the model effectively classifies "Mine" and "Rock" instances, achieving good accuracy and a balanced F1-Score. The adjusted metrics provide a clearer picture of your model's performance, and you can further tailor the model based on the specific needs of your project.
