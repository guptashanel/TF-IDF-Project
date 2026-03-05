Overview-

This project demonstrates a basic NLP text classification pipeline using TF-IDF vectorization and Multinomial Naive Bayes.
The model classifies text into Positive or Negative sentiment based on word importance.

Technologies Used

Python

spaCy (tokenization & stopword removal)

scikit-learn

TfidfVectorizer

MultinomialNB

pandas (matrix visualization)

 Workflow

Text Preprocessing

Convert text to lowercase

Remove stopwords and punctuation

TF-IDF Vectorization

Converts text into numerical features

Assigns importance to words based on frequency

Model Training

Multinomial Naive Bayes trained on TF-IDF features

Prediction

New text is transformed and classified as Positive or Negative