# MEDICINE-REVIEW---SENTIMENT-ANALYSIS-using-LIGHT-GBM-MODEL-
Building a medicine review sentiment analysis model using LightGBM (Light Gradient Boosting Machine) classifier can be a great approach. LightGBM is known for its efficiency and effectiveness in handling structured data, making it suitable for this task.

Here's a step-by-step process to build the model:
1. Data Collection and Preprocessing:
* Gather a dataset of medicine reviews. You can find such datasets on platforms like Kaggle or through web scraping from medicine review websites.
* Preprocess the data by cleaning text, removing special characters, converting text to lowercase, tokenizing, removing stop words, and stemming or lemmatizing the words.
2. Feature Extraction:
* Use rating columns as Sentiment after createting a New column using feature Enginnering technique.
* You may also consider other features like review length, sentiment scores, etc.
3. Split Data:
* Split the dataset into training and testing sets to evaluate the model's performance.
4. Train LightGBM Model:
* Initialize and train an LightGBM classifier on the training data.
* Tune hyperparameters like learning rate, maximum depth, and number of estimators using techniques like grid search or random search to optimize performance.
5. Evaluate Model:
* Evaluate the trained model on the testing data using metrics like accuracy, precision, recall, F1-score, and confusion matrix.
6. Improve Model (if necessary):
* If the model performance is not satisfactory, consider adjusting hyperparameters, feature engineering, or using more advanced techniques like ensemble methods.

What is LightGBM?

LightGBM is an open-source, distributed, high-performance gradient boosting framework developed by Microsoft. It is designed for efficiency, scalability, and accuracy. It is based on decision trees designed to improve model efficiency and reduce memory usage. It incorporates several novel techniques, including Gradient-based One-Side Sampling (GOSS), which selectively retains instances with large gradients during training to optimize memory usage and training time. Additionally, LightGBM employs histogram-based algorithms for efficient tree construction. These techniques, along with optimizations like leaf-wise tree growth and efficient data storage formats, contribute to LightGBM’s efficiency and give it a competitive edge over other gradient boosting frameworks.
