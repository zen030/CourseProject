**Hint: Download the PDF files to view it**
# 1.	Project Result Summary
The project score outperforms the baseline score on the project competition Leaderboard.
- The project **F1 score**: 0.757905138339921
- The baseline **F1 score**: 0.723

# 2.	Project Team Member
- Name: Zainal Hakim
- NetID: zainalh2

# 3.	Project Topic
The project topic falls under the Text Classification Competition option. 

The main goals of this project:
1.	To explore sentiment analysis using a state-of-the-art method
2.	To beat the baseline score using the given training and sample datasets

# 4.	Sentiment Classifier using BERT
Bidirectional Encoder Representations from Transformers (BERT) is a state-of-the-art pre-training Natural Language Processing (NLP) model developed by Google. In this project, sentiment analysis uses BERT to detect sarcasm in Twitter tweets.

# 5.	Programming Language & Library
The project uses:
- Python 3.8 programming language to implement software code.
- Huggingface library: https://huggingface.co

# 6. Previous Experience with BERT
I have no previous experience with BERT nor with Deep Learning.
I have a little experience with the Python programming language and the Pandas library.

# 7. Important File(s)
The <b>FINAL</b> trained models:
1. BERT <b>LARGE</b> uncased model: https://drive.google.com/file/d/1EMcBXsFPqOVg4w_-Nob4ebWA0qTr9SLQ/view?usp=sharing
2. BERT <b>Base</b> uncased model: https://drive.google.com/file/d/1--_k6QVpRIV3HtP-PzWjm9066ebtmA8S/view?usp=sharing

The hyperparameters in my experiments are:
-	Learning rate: 2e-5
-	Batch size: 5 (considering memory size) 
-	Epochs: 4 iterations
-	Epsilon: 1e-8
-	Random seed value: 17

# 8. Demo
Demo video is available:
- Here https://drive.google.com/file/d/1PAmInsMvXlgkB3jZFt9qRu-SbtsoIQBJ/view?usp=sharing 
- or here https://www.youtube.com/watch?v=PsYn2lUWpQg

# 9. Challenges
- To train and evaluate the BERT model requires computing power: a fast CPU and a large RAM size. It needs a dedicated environment such as Google Colab. To train the large models in my experiments, it requires a Google Colab PRO, which is the paid version.
- It is not easy to predict the results of the experiments since BERT is one of the Deep Learning algorithms that involves many hidden parameters. We can easily overfit the model with the given parameters and text inputs. There is no easy way to explain why one parameter performs better than the other parameter.
- Selecting a feature from the tweet to identify the sentiment is one of the most challenging parts of the project.

