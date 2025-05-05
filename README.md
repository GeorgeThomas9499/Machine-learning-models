# Machine-learning-models
Marketing Analytics
 1. Customer Segmentation

Goal: Segment customers based on behavior (e.g., frequency of purchases, total spent, preferred categories).

Techniques: Clustering (e.g., K-Means), RFM analysis.

Outcome: Understand your core customer groups for targeted marketing.

Steps Overview

1. Load and Preprocess Data: Load the CSV file(users.6M0xxK.2020.public.csv) , handle missing values, and clean data.

2. Feature Engineering:
  * Recency: Use seniorityAsDays (derived from seniority) as a proxy for time since last activity.
  * Frequency: Use productsBought as a proxy for purchase frequency.
  * Monetary: Use productsBought as a proxy (assuming it correlates with spending).
  * Additional Features: Include socialNbFollowers, productsWished, socialProductsLiked, and countryCode.
    
3. Data Transformation: Normalize numerical features and encode categorical ones.

4. Clustering: Apply K-means clustering to segment customers.

5. Analysis and Visualization: Interpret clusters and suggest marketing strategies.

6. Output: Save the segmented dataset and provide actionable insights.
