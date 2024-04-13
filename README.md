# COGS 118B - Final Project

## Contributors:
- Audrey Liang
- Geena Limfat
- Nate Mead
- Neha Sharma
- Daphne Wu
## Abstract 
We seek to determine a model which accurately predicts the likelihood of a social media post being related to suicidal ideation. Catching behaviors that are indicative of suicidal tendencies could be crucial for early prevention and intervention of suicide completion. The dataset used contains a large body of tweets, each with a ground truth label indicating whether or not the post’s contents are related to suicide. We employed Principal Component Analysis (PCA), K-Means, and Gaussian Mixture Models (GMM), with the Elbow Method and Akaike Information Criterion (AIC) guiding us to identify two main clusters within the tweets, suggesting distinctions between those with and without suicidal ideations.Our findings were substantiated by a high F1 Score, evidencing the model’s capability in accurately classifying tweets. The Elbow Method and AIC confirmed the robustness of our clustering approach, whereas the Rand Index and Adjusted Rand Index offered insights into the clustering quality and areas for further study. Despite our effectiveness with K-Means and GMM, DBSCAN proved less suitable for this dataset. Our analysis, corroborated by our various evaluation metrics, demonstrates the model’s proficiency in detecting tweets with potential suicidal ideation, underscoring the complexity and the need for nuanced analysis in this critical area of mental health monitoring.
