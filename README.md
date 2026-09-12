# emotion-classification
Machine Learning models for emotion classification using text data.
## Dataset
- Source:nlp_dataset.csv
- Preprocessing: Lowercasing, punctuation removal, tokenization, stopword removal.

## Feature Extraction
- **TF-IDF Vectorizer**: Converts text into numerical features, emphasizing rare but important words.

## Models
- **Naive Bayes**: Fast, works well with text data.
- **Support Vector Machine (Linear Kernel)**: Handles high-dimensional sparse data effectively.

## Results
- Naive Bayes Accuracy: XX% | F1-score: YY
- SVM Accuracy: AA% | F1-score: BB
- SVM performed better overall for emotion classification.

## Files
- `Emotion_Classification.ipynb` → Jupyter Notebook with code.
- `best_model.pkl` → Saved best model.
- `emotions.csv` → Dataset (optional, or load via Google Drive)


