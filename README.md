# Comment-Toxicity-Model
Comment Toxicity Classification Model
This project is a supervised deep learning model built using TensorFlow and Keras, aimed at classifying online comments into multiple categories of toxicity such as:

Toxic
Obscene
Insult
Threat
Identity Hate
Severe Toxic

The model was trained on the Jigsaw Toxic Comment Classification Challenge dataset from Kaggle.

Problem Statement:
The internet is full of valuable discussions, but unfortunately also has its fair share of toxic and harmful content. This project aims to build an automated system that can classify whether a comment is:

Safe and civil:
Or falls under one or more toxic categories like hate speech, threat, or insult

Dataset:
Source: Jigsaw (Kaggle)

Format: CSV with text and multi-label binary classes

Features:

comment_text (input)

6 target labels (toxic, obscene, etc.)

Technologies Used:
1. Python

2. TensorFlow / Keras

3. Pandas, NumPy, Matplotlib

4. Text Vectorization using TextVectorization layer

5. Gradio (optional) for UI demo

Project Workflow:
1. Data Preprocessing

2. Clean and normalize text

3. Vectorize using Keras TextVectorization

4. Model Building

5. A deep neural network with embedding, LSTM, and dense layers

6. Multi-output sigmoid layer for multi-label classification

Training:

1. Optimized using Adam

2. Binary crossentropy loss for each label

3. Metrics: AUC, Accuracy

Evaluation:

1. Model evaluated on validation/test split

2. ROC-AUC for each class

Deployment Ready: 

1. Model saved as toxicity.h5

2. Compatible with deployment using Gradio or Streamlit
