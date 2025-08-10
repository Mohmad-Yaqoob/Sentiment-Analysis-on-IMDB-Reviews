# IMDB Movie Reviews Sentiment Analysis 🎬📝

This project uses an **LSTM-based deep learning model** to classify IMDB movie reviews as **positive** or **negative**.

---

## 📌 Dataset  
We use the [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) from Kaggle.  
- **50,000 reviews**  
- Balanced classes (25k positive, 25k negative)  

---

## 🚀 Features  
- Downloads dataset using Kaggle API  
- Preprocesses text with tokenization and padding  
- LSTM model for sentiment classification  
- Custom prediction function for any review text  

---

## 🛠️ Installation & Setup  

pip install kaggle pandas scikit-learn tensorflow


## 🧠 Model Architecture
- Input Layer: Shape (200,)
- Embedding Layer: input_dim=5000, output_dim=128
- LSTM Layer: 128 units, dropout=0.2, recurrent_dropout=0.2
- Dense Layer: Sigmoid activation
## 📊 Results
Training Accuracy: 89.13%
Training Loss: 0.2637
Testing Accuracy: 88.71%
Testing Loss: 0.2763

