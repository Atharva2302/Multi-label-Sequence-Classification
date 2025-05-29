# Multi-label-Sequence-Classification
## 📁 Project Contents

- `Multilable_Classification_project_Atharva.ipynb`: The complete Jupyter notebook with data analysis, model building, training, evaluation, and error analysis.

## 📊 Dataset

The dataset is sourced from biomedical research papers (PLOS Journal). It includes tokens labeled in BIO format for Named Entity Recognition:

- `B-O`: Non-entity token
- `B-AC`: Abbreviation start
- `B-LF`: Long form start
- `I-LF`: Continuation of long form

## 🧪 Experiments Conducted

- **Vectorizers**: CharNGram, Word2Vec
- **Algorithms**: Feed-Forward Neural Network (FFNN), SVM
- **Loss Functions**: Hinge, SGD, Adam, RMSProp
- **Batch Sizes & Epochs**: Multiple combinations tested for optimal performance

## ✅ Key Results

- **Best Configuration**: Word2Vec + FFNN + Hinge Loss
- **Accuracy**: ~91%
- **F1 Score**: ~0.92
- **Common Challenges**: Class imbalance, especially misclassification of rare tags like `I-LF`

## 📊 Visualisations

- POS and NER Tag Distributions
- Sentence Length Charts
- Word Clouds
- Confusion Matrices
- Error Analysis Heatmaps

## 🚀 Tools & Libraries

- Python (Jupyter Notebook)
- TensorFlow / Keras
- Gensim (Word2Vec)
- Seaborn & Matplotlib (for visualisations)
- Scikit-learn
- SpaCy

## 👨‍💻 Author

**Atharva Sapkal**  

---
