
# Customer-Marketing Segmentation with Machine Learning

This project utilises unsupervised machine learning tools to segment credit card customers based on their usage characteristics. The insights from customer segmentation can then be leveraged by the marketing department to tailor products and services specific to these customer segments. This project is part of Technopreneurial Marketing under Prof. Mamoni Banerjee.

## Dataset
The project employs a dataset of approximately 9000 credit card users, capturing various aspects of their credit card usage practices.

## Objective
The primary objectives are to:
1. Analyze the dataset.
2. Define customer segments based on consumption behaviours using machine learning and dimensionality reduction techniques.

## Methods Implemented
Several unsupervised machine learning tools are implemented, including:
- **K-Means Clustering**: The optimal number of segments is determined using the Elbow method.
- **Principal Component Analysis (PCA)**: Applied for dimensionality reduction.
- **Autoencoder**: A simple encoder-decoder fully connected network in Keras is used for dimensionality reduction.

## Project Structure
1. **Data Exploration**:
   - Data wrangling and cleaning.
   - Data analysis and visualization to identify salient elements, trends, and correlations.
2. **K-Means Application**:
   - Determining the optimal number of clusters using the Elbow method.
3. **Principal Component Analysis**:
   - Dimensionality reduction to visualize data in fewer dimensions.
4. **Autoencoders**:
   - Further dimensionality reduction using an encoder-decoder network.

## Results
### Customer Segments Identified
- **Revolvers**: Use credit card as a loan, with high balances and cash advances, low purchase frequency, high cash advance frequency and transactions, and low percentage of full payment.
- **Credit Purchasers**: High purchase frequency, frequent use of payment installment facilities, and a moderate percentage of full payment.
- **Active Cash Buyers**: High purchase frequency, active buyers who pay in full, with the highest percentage of full payment.
- **VIP/Prime**: High credit limit and highest percentage of full payment, ideal targets for increased credit limit and spending.
- **Low Tenure**: Customers with low tenure, low balance.
- **Transactors**: Customers who pay the least interest charges, careful with their money, with low balances and cash advances.
- **One-Off**: Customers with record-high minimum payment levels.
- **Low Activity**: Customers using their cards the least, with the lowest purchase frequency and amounts.

### Key Segment Characteristics
- **VIP/Prime** and **One-Off** clusters are very small, representing outliers and unlikely potential market segments.

### Visualizations
- **Customer Segments**:
  ![segments](https://github.com/boonmo/Customer-Segmentation-Analysis-with-Targeted-Marketing/assets/133490509/ab87b72d-7ee9-43bd-a66f-99debcb052c3)

  
- **Population Per Segment**:
  ![population](https://github.com/boonmo/Customer-Segmentation-Analysis-with-Targeted-Marketing/assets/133490509/6f81e676-b3a4-49d2-a980-84dcd62184cc)

  
- **PCA Projection**:
  ![pca](https://github.com/boonmo/Customer-Segmentation-Analysis-with-Targeted-Marketing/assets/133490509/169302ed-2713-4fc6-92f6-64209db9ad95)


## Key Results from Customer Segmentation Analysis
The K-Means clustering algorithm identified 4 distinct customer segments:

1. **Segment 1 - Young Urban Professionals**: Younger customers, predominantly in their 20s and 30s, living in urban areas with higher incomes and education levels. They tend to be tech-savvy and engage more with digital marketing channels.
2. **Segment 2 - Middle-Aged Family Shoppers**: Middle-aged customers, often married with children, who have moderate incomes and education levels. They tend to be more price-conscious and responsive to traditional marketing tactics.
3. **Segment 3 - Older Affluent Customers**: Older, retired customers with high incomes and education levels. They have more disposable income and prefer premium products and services.
4. **Segment 4 - Price-Sensitive Value Seekers**: Younger, lower-income customers who are very price-sensitive and seek the best value for their money. They are less engaged with marketing and more likely to use online comparison tools.

## Segment Profiling and Recommendations
The code provides detailed profiles of each customer segment, including their demographic characteristics, shopping behaviours, media consumption habits, and brand preferences. Based on these insights, the following recommendations are made:

- **Segment 1 (Young Urban Professionals)**: Target with digital marketing campaigns, social media advertising, and personalized product recommendations.
- **Segment 2 (Middle-Aged Family Shoppers)**: Reach through traditional marketing channels like print ads, direct mail, and in-store promotions emphasizing value and family-oriented messaging.
- **Segment 3 (Older Affluent Customers)**: Offer premium products and services, focusing on high-touch customer service and exclusive experiences.
- **Segment 4 (Price-Sensitive Value Seekers)**: Provide clear pricing information, discounts, and budget-friendly product options to address their price sensitivity.

By leveraging these segmentation insights, the company can develop more targeted and effective marketing strategies to better meet the needs of its diverse customer base.
