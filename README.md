# Vietnamese Sentiment Analysis with PhoBERT

## Description
This project leverages the PhoBERT model to perform sentiment analysis on Vietnamese text data. PhoBERT, a transformer-based model pre-trained specifically on Vietnamese language data, is utilized to classify sentiments into positive, negative, or neutral categories.

## Methodology

### Data Preparation
1. **Dataset Collection**: The dataset consists of Vietnamese text data labeled with sentiment categories.
2. **Preprocessing**: Text data is cleaned and preprocessed, including tokenization, removing special characters, and lowercasing.

### Data Splitting
- The dataset is split into training and testing sets to evaluate model performance. A typical split ratio is 80:20.

### Model Building
- **PhoBERT Model**: The PhoBERT model is fine-tuned for sentiment analysis. The model architecture includes multiple transformer layers followed by a dense layer for classification.

### Model Training
- The model is trained on the training dataset, with hyperparameters tuned for optimal performance. The training process involves fitting the model to the data for a specified number of epochs.

### Performance Evaluation
- **Metrics**: Various performance metrics such as accuracy, precision, recall, and F1-score are calculated to assess the model's performance.
- **Confusion Matrix**: A confusion matrix is generated to visualize the model's classification results.

### Visualization
- **Training vs Validation Accuracy**: Plots are created to show the training and validation accuracy over epochs.
- **Training vs Validation Loss**: Plots are created to show the training and validation loss over epochs.

### Future Work
- Potential improvements include experimenting with different model architectures, increasing the dataset size, and applying data augmentation techniques to enhance model performance.

## Conclusion
This project demonstrates the capability of the PhoBERT model in performing sentiment analysis on Vietnamese text data. By fine-tuning a pre-trained transformer-based model, it is possible to achieve high accuracy in classifying sentiments, which can be beneficial for various applications such as market analysis, customer feedback analysis, and social media monitoring.
