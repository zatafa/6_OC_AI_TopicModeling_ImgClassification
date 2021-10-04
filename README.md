# :dart: Natural Language Processing & Computer Vision
- NLP : Topic modeling, with the goal to identify what is discussed by the customers in bad reviews;
- CV : Image classification, with the goal to classify automaticaly the pictures published by customers (5 categories).

# :card_index_dividers: Dataset
[Yelp Open Dataset](https://www.yelp.com/dataset)

<img src=".\pictures\yelp_open_dataset.png">

# :scroll: Tasks
## Topic Modeling
- :heavy_check_mark: Preprocessing : Tokenization, Stopwords, Lemmatization, Bigrams, Bag-of-words (BOW);
- :heavy_check_mark: Use of Latent Dirichlet Allocation (LDA): find optimal number of topics, build LDA, visualize results.

## image Classification
- :x: We don't use SIFT or ORB but CNN (Convolutional Neural Network)
- :heavy_check_mark: Prepare image folders structure to ease the data generation (input pipeline);
- :heavy_check_mark: Use of Google Colab Pro to leverage from its GPU;
- :heavy_check_mark: Use of VGG-16 pre-trained CNN from Keras (with Tensorflow backend);
- :heavy_check_mark: Apply transfer learning methods for the classification of the images: feature extraction + (partial) fine-tuning
- :heavy_check_mark: Evaluate model predictions (especially mistakes)

# :computer: Dependencies
Google Colab GPU, Pandas, Numpy, matplotlib, scikit-learn, NLTK, Spacy, Gensim, WordCloud, Keras, Tensorflow

# :pushpin: References 
- [Get started with SPACY](https://spacy.io/usage)
- [Get started with NLTK](https://www.nltk.org/)
- [Get started with GENSIM](https://radimrehurek.com/gensim/)
- [Get started with AI fundamentals in Azure](https://docs.microsoft.com/fr-fr/learn/modules/get-started-ai-fundamentals/)