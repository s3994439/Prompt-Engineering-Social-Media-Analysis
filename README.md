# Prompt-Engineering-Social-Media-Analysis

This project explores how prompt engineering is discussed across Reddit and YouTube, combining natural language processing (NLP), sentiment analysis, topic modeling, and social network analysis. The goal is to extract insights into trends, influence patterns, and community behavior related to prompt engineering in the context of generative AI tools like ChatGPT.

##  Overview

The project analyzes over 50,000 social media comments related to prompt engineering. It includes:

- **Data Collection** from Reddit and YouTube APIs.
- **Preprocessing**: cleaning, lemmatization, normalization, and time-series structuring.
- **Sentiment Analysis** using both rule-based (VADER) and count-based methods.
- **Topic Modeling** via Latent Dirichlet Allocation (LDA) with interactive pyLDAvis visualizations.
- **Social Network Analysis** on reply networks to detect communities and track influence propagation using Independent Cascade and Linear Threshold models.

##  Techniques Used

- **Natural Language Processing**: text normalization, tokenization, lemmatization.
- **Sentiment Analysis**: VADER, positive/negative word matching, sentiment time series.
- **Topic Modeling**: LDA with coherence analysis and visualization.
- **Network Analysis**: Graph construction with NetworkX, centrality metrics, community detection.
- **Influence Propagation**: IC and LT models on reply networks.
- **Visualization**: Word clouds, boxplots, time series, pyLDAvis, and network diagrams.



## 🔍 Key Insights

- Prompt engineering discussions are heavily influenced by trending AI tools and platforms.
- Reddit communities exhibit more polarized sentiment than YouTube.
- Key influencers and central figures emerge in both Reddit and YouTube networks, often tied to high engagement threads.
- Topics range from prompt syntax optimization to ethical concerns about automation and AI alignment.
