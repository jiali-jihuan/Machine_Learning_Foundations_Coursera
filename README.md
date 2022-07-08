## Machine Learning Foundations - Coursera - University of Washington
<br><b> Specialization Track Notes </b>

- Course 1: Machine Learning Foundations: A Case Study Approach
  - Regression Modeling
    - Evaluation techniques:
      - RSS (residual sum of squares)
      - Train test split
      - Training error vs test error
  - Classification
    - Evaluation techniques:
      - error = #mistakes/ total#
      - accuracy = #correct/ total#
      - confusion matrix
      - precision = TP/(TP+FP)
      - recall = TP/(TP+FN)
      - ROC curve
      - F1 score = 2*P*R/P+R , P = precision, R = recall
      - confidence level
  - Similarity
    - BOW (word count)
      - emphasis on rare words, TF-IDF
        - log( #docs/(1 + #docs using word) )
      - nearest neighbor (most)
      - k-nearest neighboe - top N (K-means)
    - Recommender Systems
      - precision/recall curves for metric
      - AUC or precision (precision only if limited # recommendations)
      - collaborative filtering
