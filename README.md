# Studying ecology's semantic changes through Swiss newspapers between 1970 and 2020

## Abstract

Since its gradual appearance in the public arena in the mid- to late-sixties, ecology gained prominence on the public scene, becoming an unavoidable issue in political debates. Throughout time it has been used to deal with various societal issues reflecting contemporary concerns. Based on long-established knowledge about the ability of language and words' usage to model cultural evolution, we computationally analyze the evolution of ecology's representation in french speaking Swiss society through \textit{écologie} semantic changes within a corpus of newspaper articles. Word embedding reveals observable qualitative drifts in the word's usage. Nonetheless a quantitative approach depending on topic modeling unveils more nuanced results. 

## Git contents


- ´data´ folder: contains all the articles scraped from e-newspaperarchives.ch.
- ´0_scrap_newspapers.ipynb´: scrap newspapers from e-newspaperarchives.ch.
- ´1_exploration.ipynb´: data exploration and basic statistics
- ´2_preprocessing_LDA.ipynb´: articles pre-processing into corrected tokens for LDA and visualisation
- ´3_word2vec.ipynb´: embed the articles in wordspaces using Word2Vec
- ´4_viz.ipynb´: visualization of the wordspaces
- ´5_topicmodeling.ipynb´: LDA analysis
