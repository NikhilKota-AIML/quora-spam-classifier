# Quora Spam Classifier
This project builds a deep learning model using LSTM to detect spam questions on Quora using text data and pre-trained word embeddings.
Due to GitHub file size limits, download the required data here:
https://drive.google.com/file/d/1haR6_QXX1oQ2QCFFAPQdDORTPwI4xm7H/view?usp=drive_link
https://drive.google.com/file/d/1bEkK6-QF6TLCwN-tdmAoWtAiqzoALeAp/view?usp=drive_link
Model Overview:
- Embedding layer (GloVe pre-trained vectors)
- LSTM layer (64 units)
- Dropout (0.3)
- Dense output layer with Sigmoid
Trained using binary cross-entropy loss and Adam optimizer.
Performance:
-Metric              Value     
-Train Accuracy      95.56%
-Validation Accuracy 95.69%
-Validation Loss     0.1111
Files:
- quora_spam_classifier.ipynb - Full Colab notebook
- quora_spam_model.h5 - Trained model
- quora_spam_model.keras - Trained model
- README.md – Project summary and links
How to Run:
Download "train.csv" and "glove.6B.100d.txt" from Google Drive links above.
Upload them to your Google Colab environment.
Open and run "quora_spam_classifier.ipynb" step by step.
Final model will be saved as "quora_spam_model.h5".
