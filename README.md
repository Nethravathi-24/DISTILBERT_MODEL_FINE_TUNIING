# Fine-Tuning DistilBERT on IMDb Sentiment Dataset

##  Project Overview

This project demonstrates fine-tuning a pre-trained DistilBERT model for sentiment analysis using the IMDb movie reviews dataset. The goal is to classify movie reviews as **positive** or **negative** and compare different fine-tuning strategies.

This project was completed as part of an NLP internship assignment on BERT fine-tuning.


##  Objective

- Perform text preprocessing on a real-world dataset
- Tokenize text using a pre-trained BERT tokenizer
- Fine-tune a transformer-based model
- Run multiple experiments
- Evaluate model performance using classification metrics
- Compare results across experiments


##  Tools & Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook


##  Dataset

Dataset Used: **IMDb Movie Reviews Dataset**

- Contains movie reviews labeled as **positive** or **negative**
- Used for binary sentiment classification
- Dataset was preprocessed to remove missing values and clean text

---

##  Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Train-Validation-Test Split
4. Tokenization using BERT tokenizer
5. Model Training
6. Model Evaluation
7. Confusion Matrix Visualization
8. Experiment Comparison


## 🧪 Experiments Performed

### Experiment 1 — Freeze All Layers

- All transformer layers were frozen
- Only classifier layer was trained

### Experiment 2 — Fine-Tune Last 2 Layers

- Last 2 transformer layers were unfrozen
- Improved learning capability


## 📊 Evaluation Metrics

The model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix


##  Key Learnings

- Understanding BERT architecture
- Tokenization process
- Transfer learning in NLP
- Fine-tuning transformer models
- Evaluating classification models
