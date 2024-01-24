# Document-Clustering-Project-Design-Based-on-Topic-Modelling-for-News-Articles-
Data Gathering:
News articles are loaded from text files, organized into folders by category. The data is then stored in a Pandas DataFrame with columns for the news text and its corresponding category.

Accessing and Cleaning Dataset:
Checked dataset dimensions and information.
Changed the data type of the 'type' column to categorical.
Checked for and removed duplicate values.
Checked for and handled missing values.
Exploratory Data Analysis (EDA) Visualization:
Visualized the distribution of news types using histograms.
Added a word count column to the dataset.
Visualized the distribution of article lengths for different news types.
Generated word clouds to visually represent the most frequent words in each news category.
Text Processing:
Decoded UTF-8 encoded text.
Implemented a text cleaning function to lowercasing, remove HTML tags, URLs, punctuation, and extra whitespace.
Removed stopwords using NLTK and SpaCy libraries.
Text Lemmatization and Tokenization:
Used SpaCy for lemmatization.
Tokenized the cleaned text.
Latent Dirichlet Allocation (LDA) Model:
Utilized Scikit-Learn's CountVectorizer and TfidfVectorizer for document-term matrix creation.
Implemented LDA for topic modeling.
Visualized topics using word clouds.
Utilized coherence score for determining the optimal number of topics.
Latent Semantic Analysis (LSA) Model:
Performed Truncated SVD for dimensionality reduction.
Applied t-SNE for visualization.
Visualized topics using word clouds.
Gensim's LDA Implementation:
Created a dictionary and bag-of-words matrix from tokenized data.
Applied TF-IDF transformation.
Utilized Gensim's LDA for topic modeling.
Visualized topics using word clouds.
Used coherence score to find the optimal number of topics.
