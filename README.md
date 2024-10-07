# Can We Trust Consumer Ratings? Exploring the Truth Behind GameStop Reviews

## Executive Summary

This project explores consumer reviews within the gaming industry, leveraging a dataset of product reviews from a prominent retail platform. Our main goal was to discern patterns in consumer behavior and evaluate the validity of review ratings as reliable indicators of product quality. Using data preprocessing techniques like text normalization and TF-IDF vectorization, and various clustering and machine learning methods such as KMeans, DBSCAN, and ensemble models, we've unveiled insights into the dynamics of consumer ratings and recommendations.

The findings suggest that high ratings do not consistently align with positive recommendations, challenging traditional assumptions about consumer feedback in retail settings. This discrepancy provides actionable insights for retailers to refine their marketing strategies and product positioning.

## Introduction

With the rise of online retail, consumer reviews have become crucial in influencing purchasing decisions. In the gaming industry, understanding these reviews is key for retailers and developers. This project utilizes a dataset from GameStop to analyze user ratings, recommendations, and textual feedback from consumers.

The motivation behind this project is to delve into the nuances of what truly influences a consumer to recommend a product, analyzing text reviews to gauge sentiment and correlating these with ratings to identify underlying patterns.

## Methodologies

### Data Preprocessing
- **Data Extraction:** Extracted customer rating data from Gamestop website using Selenium and exported it as a CSV file containing thousands of reviews.
- **Data Import:** Importing and cleaning data from a comprehensive CSV file containing thousands of reviews.
- **Text Data Preprocessing:** Preprocessed unstructured text in the reviews contents, using tokenization, removal of stopwords, and lemmatization.

### Vectorization
- **TF-IDF Vectorization:** Transforming text data into a format suitable for model ingestion, emphasizing words that are more relevant in the reviews' context.
- **Cosine Similarity:** Measured the similarity between documents based on the frequency of words or phrases they contain using Cosine Similarity.

### Analysis Techniques
- **Feature Engineering:** Using KMeans and DBSCAN to identify patterns in consumer reviews. 
- **Dimensionality Reduction:** Applying PCA to reduce the dataset's complexity.
- **Predictive Modeling:** Employing SVM, Random Forest, and XGBoost, fine-tuned using GridSearchCV for optimal performance.

## Model Evaluation

Model performance was assessed using accuracy, precision, recall, and the F1 score. The SHAP framework helped interpret the influence of features on the predictive outcomes.

## Results and Discussion

Key Insights:
- **Review Rating Discrepancies:** High star ratings were found to not necessarily correlate with recommendations.
- **Brand Popularity and Consumer Loyalty:** Some brands consistently received higher ratings, pointing to strong brand loyalty.
- **Clustering Patterns:** Identifying distinct groups of reviewers, offering insights into the target customer base.

## Conclusion

This project has demonstrated the potential of data analytics in revealing insights from consumer reviews in the gaming industry. Advanced analytical techniques highlighted discrepancies between ratings and recommendations and identified brand loyalty indicators.

## Future Work

Future research could include:
- **Temporal Analysis of Reviews:** To understand trends over product life cycles.
- **Expansion of Data Sources:** To enhance model generalizability.
- **Integration with Sales Data:** To correlate reviews with sales performance.
- **Advanced Machine Learning Techniques:** Employing more sophisticated algorithms to deepen the analysis.

**To review the scripts, please download the zip file from the master branch.**
