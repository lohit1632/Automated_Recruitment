**Sales Position Candidate Classification Model**

**Introduction:**
This project aims to develop a classification model to predict whether a candidate should be hired for a sales position at Piramal Finance. The model utilizes both basic machine learning (ML) and deep learning (DL) techniques along with natural language processing (NLP) for text data extraction from resumes.

**Dataset:**
- The training data is stored in a CSV file named `train.csv`.
- The `CV_Train` folder contains resumes of all candidates applying for the sales position.

**Workflow:**
1. **Data Collection:**
   - The training dataset includes candidate names and relevant features for classification.
   - Resumes are collected from the `CV_Train` folder.

2. **Text Data Extraction:**
   - Basic NLP techniques are employed to extract information from resumes.
   - Extracted text features are added to the existing DataFrame.

3. **Data Preprocessing:**
   - Various columns in the CSV file are processed, converting text to meaningful data.
   - Encoding techniques such as label encoding or target mean encoding are applied to categorical variables.

4. **Handling Missing Data:**
   - Missing data is identified and handled appropriately using techniques like imputation.

5. **Model Training:**
   - A Random Forest classifier is trained on the processed data to predict the suitability of candidates for the sales position.
   - Hyperparameter tuning may be performed to improve model performance.

6. **Evaluation:**
   - The model's performance is evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score.
   - Cross-validation techniques may be employed to ensure the model's robustness.

**Files:**
- `train.csv`: Contains the training data with candidate information.
- `CV_Train` folder: Contains resumes of candidates.
- `preprocess.py`: Python script for data preprocessing.
- `model.py`: Python script for model training and evaluation.

**Usage:**
1. Ensure Python environment with necessary libraries is set up.
2. Run `preprocess.py` to preprocess the data.
3. Execute `model.py` to train the classification model and evaluate its performance.

**Results:**
- The trained model's performance metrics are documented.
- Model predictions on the test dataset are stored for further analysis.

**Conclusion:**
This project demonstrates the development of a classification model for hiring suitable candidates for sales positions at Piramal Finance. By leveraging ML, DL, and NLP techniques, the model provides valuable insights for decision-making in the hiring process.

**Future Improvements:**
- Experiment with different machine learning algorithms to improve model performance.
- Incorporate advanced NLP techniques for better feature extraction from resumes.
- Enhance data preprocessing techniques to handle diverse datasets effectively.
- Deploy the model in a production environment for real-time candidate evaluation.

**Contributors:**
- Lohit Pattnaik
  
**Special Thanks:**
- I would like to thank **Piramal Finance** to give us this project to work upon
