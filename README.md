# Does-this-Incident-Matter

A deep neural network by using a CNN based model and introducing an attention mechanism for trivial incident prediction.

## Introduction

This project is to implement the deep learning model in the paper, which proposes a deep-learning based approach, called DeepTIP(Deep learning based Trivial Incident Prediction), to prioritizing incidents by identifying trivial incidents and effectively utilizes the three types of features to identify trivial incidents. `DeepTIP.ipynb`

<br/></br>
![Architecture](Overviewpng.png) </br>
<center>The overview of the network </center>

## Compared Approaches

1. Menzies and Marcus, which first applies the standard text mining method to process textual descriptions inreports, and then uses tf-idf (term frequency-inverse docu-ment frequency) to transform the textual description ina report to a vector. Finally, it uses the rule classifier basedon entropy and information gain to predict bug severity.`Baseline_Rule.ipynb`

2. Lamkanfi et al., which applies the standard text miningmethod to process text descriptions. Then, it counts tokenfrequency and uses the Naive Bayes algorithm to predictbug severity.`Baseline_Bayes.ipynb`

3. Zhang at al., which applies the standard text miningmethod and calculates the similarities between a new bugreport and historical bug reports using BM25F and LDA(Latent Dirichlet Allocation). According to the similar-ities, it infers the bug severity based on the top-k nearestneighbors among historical reports (KNN).`Baseline_KNN.ipynb`

## Thanks
