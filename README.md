# Content_Based_Recommender
Content Based Recommendation System for News articles


The data has following fields:
Article_Id : Id of an article
Title : Title of an article
Author : Author of an article
Date : Date of publication of an article
Content : Body of an article
URL : URL of an article


The Code helps you build 3 different types of content based recommendation systems:-

TF-IDF (term frequency-inverse document frequency) based News Recommender
A token refers to the smallest entity in an article and each token has an associated tf-idf value which determines the importance of that token in the corpus. Each article is represented in terms of a TF-IDF vector in order to compute the recommendations.

NER (named entity recognition) based News Recommender
Nouns define the entities such as a person, organization, location in an article. Each article is represented in terms of nouns to generate recommendations.

Topic based News Recommender
Rather than modelling an article as a bag of words (that is syntactic in nature), topic models generate a semantic level representation of an article, as a mix of topics where every topic has a probability associated with it (a measure of how important the topic is to the article). Each topic is defined as a multinomial probability distribution over the corpus vocabulary. The probabilities reflect the importance of a word in a topic. Each article is represented in terms of a Topic vector to generate the recommendation.

Hybrid News Recommender
Above mentioned techniques to generate recommender can be combined to compare how different the recommender behaves when compared to the base models.

Evaluation
Recommenders are evaluated by comparing how close the recommended articles are to the articles read in the past. We also compare the articles recommended by different recommenders to get a glimpse of underlying mechanics of different recommender types.
