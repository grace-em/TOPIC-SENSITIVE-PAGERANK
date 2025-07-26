## Topic-Sensitive PageRank for Personalized Web Search

This project explores **Topic-Sensitive PageRank (TSPR)** as an extension of the classic PageRank algorithm to support personalized web search. By biasing the teleportation vector based on topic relevance, TSPR delivers more user-aligned search results.

### Features

* Implementation of TSPR using Python and NetworkX
* Biased random walks on a web graph with topic-specific teleportation vectors
* Support for user profile-based personalization
* Comparative evaluation against traditional PageRank using Spearman and Jaccard metrics

### Results

TSPR outperforms standard PageRank in delivering topic-relevant content, with statistically significant improvements in correlation with user preferences.

<img width="989" height="490" alt="pagerank" src="https://github.com/user-attachments/assets/7b56fbe6-2e17-4f91-bc1f-c5965b1593e0" />

### Observations

## Topic Influence:
* In Sports (TSPR), nodes A and B rise in rank.
* In Politics (TSPR), nodes C and D dominate.
* Rankings shift based on topic bias.

## Context Sensitivity:
* Standard PageRank gives a universal ranking.
* TSPR adjusts rankings dynamically for different interests.

## Personalization:
* Mimics how a personalized search engine might rank results based on user preferences.



### Applications

* Personalized search engines (e.g., Google, Bing)
* News and content recommendation systems
* Academic search and e-learning platforms

### Future Work

* Scalability through topic clustering and matrix approximation
* Integration with BERT for topic inference and dynamic personalization
* Enhancement using Graph Neural Networks
