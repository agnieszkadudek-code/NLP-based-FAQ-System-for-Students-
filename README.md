# NLP-based FAQ System for Students

An NLP-based FAQ chatbot designed to help students find information about university-related topics. The system classifies user queries into five categories and retrieves the most relevant answers from a custom FAQ dataset.

## Features

- Custom dataset of approximately 750 question–answer pairs across five categories, independently curated through research and analysis of university websites
- Text analysis and visualization using spaCy
- Comparison of four text classification approaches: Naive Bayes, Logistic Regression, SVM, and herBERT
- Comparison of four question-matching methods: n-gram similarity, TF-IDF, spaCy embeddings, and herBERT embeddings
- Answer retrieval using TF-IDF and cosine similarity
- **Recommendation of three follow-up questions related to the user's query**
- Interactive chatbot operated through the command line

## Technologies

- **Language:** Python
- **NLP:** spaCy, NLTK
- **Machine Learning:** scikit-learn
- **Deep Learning:** PyTorch, Hugging Face Transformers, herBERT
- **Data Analysis:** pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, WordCloud

## Approach

The project involved preparing a custom FAQ dataset, exploring its linguistic characteristics, and evaluating different approaches to query classification and answer retrieval.

A pretrained herBERT model was adapted for query classification, while TF-IDF combined with cosine similarity was selected as the best-performing method for answer retrieval.

## Evaluation

The models were evaluated using classification accuracy and information retrieval metrics, including Top-1 accuracy, Top-3 accuracy, and Mean Reciprocal Rank (MRR).

The herBERT-based classifier achieved **95% accuracy**, while TF-IDF with cosine similarity achieved **82.76% Top-1 accuracy** and **89.66% Top-3 accuracy** in answer retrieval.

## Key Learning Outcomes

- Natural Language Processing and text preprocessing
- Transformer-based models and transfer learning
- Text classification and information retrieval
- Dataset preparation and exploratory text analysis
- Model comparison and performance evaluation
