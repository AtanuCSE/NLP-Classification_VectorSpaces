# NLP-Classification-VectorSpaces
Code for the course "Natural Language Processing with Classification and Vector Spaces"
*(Audit Course)*

Codes are based on the topics shown in the video; however, these do not match the same techniques shown in the videos.

For example, I used Pandas and Scikit-learn while they used raw methods.

https://www.coursera.org/learn/classification-vector-spaces-in-nlp/home/welcome

- 01_Preprocessing.ipynb

    All steps of preprocessing dataset
    
- 02_logistic_regression.ipynb (Polarity)

    After the preprocessing of data, how to build matrices that can be used as features.
    
    Feature extraction with countvectorizer, tf-idf vectorizer
    
    Finally, apply logistic regression. I used Scikit-Learn
    
- 03_nfold_Cross_logistic_regression.ipynb (Polarity)

    👉🏻 nFold Cross validation on whole dataset
    
    👉🏻 **ROC Curve, Plot Confusion Matrix**
    
    👉🏻 **Hyperparameter Tuning**
    
- 04_Cosine_Similarity.ipynb

    Document by document cosine similarity <br/> The lower the better
    
    Using Fasttext and Spacy
    
 - 05_Word_Cloud.ipynb

   Word Cloud generation from Pandas column
   
 - 06_Top_Term_Frequency.ipynb

    Top words with most count values across all classes
    
 - 07_Top_Term_Metrices_Visualizer.ipynb
 
    Visualize top terms for bi-class. CDF and Hmean are used instead of only word count frequency.
  
    **Bokeh** library is used.
    
 - 08_Tep_Term_ScaledFScore_ScatterText.ipynb
 
    Find Top terms using Scaled F Score metric and plot using Scattertext library
