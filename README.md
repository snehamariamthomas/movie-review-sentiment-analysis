# Sentiment Analysis on Movie Reviews
![Alt Text](cinema.jpg)
###### Image Source: The Eagle Way

# Summary
This project focused on employing advanced sentiment analysis techniques to classify movie reviews as positive or negative, utilizing user-generated content from platforms such as IMDb. The primary objective was to enhance understanding of audience reception and improve decision-making processes for filmmakers, marketers, and streaming services.

Initially, a Naive Bayes classifier using unigrams was implemented, achieving an accuracy of 79.5% and establishing a baseline for sentiment classification. Subsequently, the analysis progressed to more sophisticated methods, including bigrams and trigrams, and incorporated lasso and ridge regression for regularization. The ridge regression model with trigrams demonstrated superior performance, attaining an accuracy of 80.5%, precision of 77.20%, and recall of 85.12%. This model’s enhanced performance underscores its effectiveness in capturing nuanced sentiment and reducing misclassifications.

These results are significant for practical applications such as predicting box office performance, refining recommendation systems, and tailoring marketing strategies. The improved accuracy and contextual understanding of the ridge regression model offer valuable insights for enhancing sentiment analysis. 

# Technical Skills and Tools
| **Aspect**           | **Details**                                                                                                          |
|------------------------|----------------------------------------------------------------------------------------------------------------------|
| **Project Focus**      | Natural Language Processing (NLP): Sentiment Analysis                                                            |
| **Programming Languages** | R                                                                                                                  |
| **Libraries and Packages** | - **Quanteda**: Text processing and feature extraction <br> - **Quanteda.textmodels**: Implementation of text classification models <br> - **Caret**: Model evaluation and performance metrics <br> - **glmnet**: Ridge and Lasso regression, regularization |
| **Data Processing**    | - **Custom Stopwords List**: Tailored stopwords for preserving sentiment-related terms <br> - **Tokenization**: Tokenizing text data and removing punctuation, URLs, numbers, and symbols <br> - **Word Stemming**: Reducing words to their root forms <br> |
| **Modeling Techniques** | - **Naive Bayes Classifier**: Initial NLP classification model using unigrams <br> - **N-grams (Bigrams, Trigrams)**: Enhanced feature extraction for capturing contextual information <br> - **Ridge Regression**: Regularized model to improve classification performance and manage complexity <br> - **Lasso Regression**: Regularization technique for feature selection and model simplicity |

