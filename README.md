# Seattle-Home-Prices-Unsupervised-Machine-Learning
![seattle](https://github.com/farisassallami/Seattle-Home-Prices-Unsupervised-Machine-Learning/assets/111199631/0b5be884-fd24-44c6-89ba-c65a8ca63999)

## Business Problem
A real estate company in Seattle wants to improve price predictions for their clients by understanding the local housing market better. They have a dataset of Seattle housing prices and want to cluster similar houses using K-means. They need to determine the optimal number of clusters using the elbow plot and Silhouette score to tailor their pricing strategies effectively.

## Business Objectives
This project utilizes TensorFlow and Keras to perform analysis on the Seattle Housing Prices dataset. It includes the implementation of K-means clustering, evaluation using Silhouette score, and visualization with an elbow plot.  We aim to

1. Improve price predictions accuracy.
2. Tailor pricing strategies based on market segments.
3. Enhance client satisfaction.
4. Gain insights into the housing market.
5. Gain a competitive edge in the industry.

## Expected Outcome:
The expected outcome is to improve price predictions, tailor pricing strategies based on market segments, enhance client satisfaction, gain market insights, and achieve a competitive edge.

## Elbow Plot Analysis:
   - Using the Elbow Plot technique to determine the optimal number of clusters for customer segmentation.
   - Applying the selected clustering algorithm for various cluster numbers and plot the corresponding sum of squared distances.
   - Identifying the elbow point where the rate of decrease in the sum of squared distances significantly diminishes.

     ![g1](https://github.com/farisassallami/Seattle-Home-Prices-Unsupervised-Machine-Learning/assets/111199631/cdebfb4b-a4fb-47f4-83c2-a41b881db9c4)
     
-  The inertia plot does not have a very pronounced elbow at any number, but the graph seems to bend at 4 to 5 clusters.

## Silhouette Score Evaluation:
   - We will Calculate the Silhouette Score for each clustering solution.
   - We will Compare the scores to determine the clustering solution that maximizes the separation between clusters while maintaining their compactness.

   ![g2](https://github.com/farisassallami/Seattle-Home-Prices-Unsupervised-Machine-Learning/assets/111199631/8d42653e-8acd-4c5f-924c-ba54c4bcfbfb)

   - The graph shows that 4 or 5 would be good candidates for the number of clusters since it has they have the highest Silhouette Scores, so we will select 4 clusters.

## Clusters of House Sales visualizations

### Sales Price vs Total Square Footage
![g3](https://github.com/farisassallami/Seattle-Home-Prices-Unsupervised-Machine-Learning/assets/111199631/666bcc8a-c9c9-4993-93d8-62b6b89d318e)

We can see the higher total square footage on the property tends to sell for more.

### Sales Price vs Year Built
![g4](https://github.com/farisassallami/Seattle-Home-Prices-Unsupervised-Machine-Learning/assets/111199631/7a785a52-24ba-4882-a0d2-6ecfbb1d596e)

We can see that the newer the house is the more the property sells fore.

