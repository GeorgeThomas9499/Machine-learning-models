# Machine-learning-models
Marketing Analytics
 1. Customer Segmentation

Goal: Segment customers based on behavior (e.g., frequency of purchases, total spent, preferred categories).

Techniques: Clustering (e.g., K-Means), RFM analysis.

Outcome: Understand your core customer groups for targeted marketing.

Steps Overview

Load and Preprocess Data: Load the CSV, handle missing values, and clean data.

Feature Engineering:

Recency: Use seniorityAsDays (derived from seniority) as a proxy for time since last activity.

Frequency: Use productsBought as a proxy for purchase frequency.

Monetary: Use productsBought as a proxy (assuming it correlates with spending).

Additional Features: Include socialNbFollowers, productsWished, socialProductsLiked, and countryCode.

Data Transformation: Normalize numerical features and encode categorical ones.

Clustering: Apply K-means clustering to segment customers.

Analysis and Visualization: Interpret clusters and suggest marketing strategies.

Output: Save the segmented dataset and provide actionable insights.
