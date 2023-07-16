# Amazon Fashion Recommendation Engine.

(case studies), Recommendation systems for Amazon Fashion products using various NLP techniques and machine learning methodologies.

# Project Overview

This project aims to develop a product recommendation engine for Amazon Fashion. The project handles various aspects of recommendation systems, including data pre-processing, text processing, similarity measures, and feature extraction.

# Technologies Used
1. Python
2. Numpy
3. Pandas
4. NLTK
5. Sklearn
6. TensorFlow
7. Keras
8. Seaborn
9. Matplotlib
   
# Features

1. Text-based product similarity
2. Bag of Words (BoW) on product titles
3. TF-IDF-based product similarity
4. IDF-based product similarity
5. Text Semantics-based product similarity
6. Average Word2Vec product similarity
7. IDF weighted Word2Vec for product similarity
8. Weighted similarity using brand and color
9. Visual features based on product similarity
    
# Dataset
The dataset used in this project comes from the Amazon Fashion section. The initial dataset had approximately 183K entries, but due to computation limitations, the project uses a subset of 28K entries for processing and modeling.

# Methodology:

1. Data Processing: Initially, the data was reduced from 183K entries to 28K entries for efficient processing.
2. Remove Near Duplicate Items: In this step, the data is cleaned by removing near duplicate items to ensure the integrity and quality of the recommendations.
3. Text Pre-processing: The text is preprocessed to remove special characters and stopwords. Stemming is also performed on the text data.
4. Text-Based Product Similarity: The similarity between products based on their text description is computed using different methodologies:

  1. Bag of Words (BoW)
  2. TF-IDF (Term Frequency-Inverse Document Frequency)
  3. IDF (Inverse Document Frequency)
  4. Text semantics using word2vec
  
6. Feature Extraction: The TensorFlow and Keras libraries are used to extract the visual features from the product images.
7. Visual Features-Based Product Similarity: The similarity between the products based on their visual features is computed.
8. Combining Brand and Color Features: The brand and color features are also considered and combined with the textual and visual features for the final recommendation system.
9. Recommendation Engine: Based on the textual, visual, brand, and color features, the recommendation engine suggests similar products.

# License:
Please see the LICENSE file for details.

# Contact:
For any queries, please feel free to reach out to us at mostafathemar@email.com.
