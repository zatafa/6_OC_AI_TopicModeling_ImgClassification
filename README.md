# :dart: Natural Language Processing & Computer Vision
- NLP : Topic modeling, with the goal to identify what is discussed by the customers in bad reviews;
- CV : Image classification, with the goal to classify automaticaly the pictures published by customers (5 categories).

# :card_index_dividers: Dataset
[Yelp Open Dataset](https://www.yelp.com/dataset)

<img src=".\pictures\yelp_open_dataset.png">

# :scroll: Tasks
## :abc: Topic Modeling
- :heavy_check_mark: Preprocessing : Tokenization, Stopwords, Lemmatization, Bigrams, Bag-of-words (BOW);
- :heavy_check_mark: Use of Latent Dirichlet Allocation (LDA): find optimal number of topics, build LDA, visualize results.

<img src=".\pictures\lda_topic_modeling.png"><img src=".\pictures\topic_worldCloud.png">

## :framed_picture: Image Classification
- :x: I don't use SIFT or ORB;
- :heavy_check_mark: I use CNN (Convolutional Neural Network);
- :heavy_check_mark: Prepare image folders structure to ease the data generation (input pipeline);
- :heavy_check_mark: Use of Google Colab Pro to leverage from its GPU;
- :heavy_check_mark: Use of VGG-16 pre-trained CNN from Keras (with Tensorflow backend);
- :heavy_check_mark: Apply transfer learning methods for the classification of the images: feature extraction + fine-tuning;
- :heavy_check_mark: Evaluate model predictions (especially mistakes).

<img src=".\pictures\vgg16_structure.png">

<img src=".\pictures\feature_learning_vs_fine_tuning.png">

# :computer: Dependencies
Google Colab GPU, Pandas, Numpy, matplotlib, scikit-learn, NLTK, Spacy, Gensim, WordCloud, Keras, Tensorflow

# :pushpin: References 
- Yelp : [Yelp for developers](https://www.yelp.com/developers?country=US); [Get Yelp API key](https://ultimateelementor.com/docs/get-yelp-api-key/);
- [Get started with SPACY](https://spacy.io/usage), [Get started with NLTK](https://www.nltk.org/), [Get started with GENSIM](https://radimrehurek.com/gensim/);
- [Get started with AI fundamentals in Azure](https://docs.microsoft.com/fr-fr/learn/modules/get-started-ai-fundamentals/);
- [Analysez vos donn??es textuelles](https://openclassrooms.com/fr/courses/4470541-analysez-vos-donnees-textuelles);
- [Classez et segmentez des donn??es visuelles - OpenClassrooms](https://openclassrooms.com/fr/courses/4470531-classez-et-segmentez-des-donnees-visuelles);
- [Courses on Keras - Python Deep Learning with Deep Lizard](https://deeplizard.com/learn/playlist/PLZbbT5o_s2xrwRnXk_yCPtnqqo4_u2YGL);
- CNN : [wikipedia](https://fr.wikipedia.org/wiki/R%C3%A9seau_neuronal_convolutif), [stanford.edu/shervine](https://stanford.edu/~shervine/l/fr/teaching/cs-230/pense-bete-reseaux-neurones-convolutionnels), [DataScientest.com](https://datascientest.com/convolutional-neural-network);
- Tensorflow : [Image classification](https://www.tensorflow.org/tutorials/images/classification?hl=fr);
- Keras : [Transfer Learning & Fine Tuning](https://keras.io/guides/transfer_learning/), [Keras pre-trained models](https://keras.io/api/applications/).