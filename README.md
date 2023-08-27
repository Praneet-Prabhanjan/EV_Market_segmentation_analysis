# EV_Market_segmentation_analysis
EV_CHARGING_STATIONS(India), EV_data sets 
Abstract : 

Market segmentation plays a role, in the advancement of emerging transportation technologies like cars (EVs). These friendly and cost effective vehicles are anticipated to witness a surge in adoption leading to increased academic interest. The main objective of this study is to explore and identify buyer segments for EVs based on factors such as their attitudes, behaviors and socioeconomic backgrounds. By employing a research framework centered around perceived benefits, attitude and intention we utilized analytical methods like cluster analysis and multiple discriminant analysis to evaluate the derived segments.

The findings of this study provide insights for scholars and policymakers who are dedicated to promoting EV adoption within the growing sustainable transportation sector. Indias EV market has experienced growth in years due to various factors. The governments focus on fostering sustainable mobility along with regulations and incentives has accelerated the adoption of EVs. Additionally rising fuel costs concerns over air pollution and advancements in battery technology have all contributed significantly to this markets expansion. However despite its potential, for growth challenges persist in Indias small EV market.

One of the challenges, in adopting vehicles is the charging infrastructure and higher initial costs when compared to traditional cars, which can cause range anxiety for consumers. However various efforts are being made by both government and industry stakeholders to address these issues through initiatives, investments, in charging infrastructure, policy support and collaborations. This shows a commitment to overcome barriers and promote adoption of vehicles.


METHODOLOGY

1. Data Gathering: Collect relevant data from a variety of sources, such as market reports, government publications, industry databases, and research papers.
• Gather information on a variety of characteristics, including vehicle type, technology, sales numbers, charging infrastructure, consumer preferences, and regional market data.

2. Data Preparation and Preprocessing:

• Remove any inconsistencies, mistakes, or missing values from the data.
• Normalize or standardize the data such that all variables are on the same scale and no variable dominates the analysis.

3. Criteria for segmentation:

• Based on the research objectives and available data, establish segmentation criteria.
• Identify relevant segmentation variables such as vehicle type, technology, sales volume, market share, charging infrastructure, and consumer preferences.

4. Principal Component Analysis (PCA): 

Use PCA to minimize the dimensionality of the dataset and discover the most significant variables.
• Use PCA to transform the original variables into a new collection of uncorrelated variables (principal components) while keeping the maximum data variance.
• Based on the explained variance ratio and scree plot analysis, determine the best number of main components.

5. Clustering with K-means:

• Apply K-means clustering to the altered data from PCA.
• Using approaches such as the Elbow method or Silhouette analysis, determine the optimal number of clusters.
• Using the K-means technique, allocate each data point to the appropriate cluster based on variable similarity.

6. Interpretation and Analysis: 

• Analyze the clustering results to understand the features and profiles of various market segments.
• Examine the variable distribution within each cluster to determine the significant differentiators.
• Determine the importance of each category based on market size, growth potential, and customer demand.
• Use statistical tests or visualizations to compare and validate the segmentation results.


In this report, we will analyze the data and answer the problem by breaking it down. 


Keywords:

EV market data, General Vehicle Type Data, Vehicle Market Data, Charging Stations Data, Vehicle Usage Statistics in Cities, etc.

Data collection: 

Dataset_1 : https://www.kaggle.com/datasets/geoffnel/evs-one-electric-vehicle-dataset 
Source - Kaggle ( https://www.kaggle.com/ )

Dataset_2: https://dataspace.mobi/dataset/electric-vehicle-charging-station-list/resource/f39bb18a-bf5b-4e93-a22e-91f13b2ad9a7 
Source - Open Government Data Platform(India) ( https://data.gov.in/ )

Market Segmentation for Electric Vehicles : 

The market segmentation strategy seeks to define actionable, manageable, homogeneous segments of individual customers to whom marketers can apply a consistent set of marketing strategies. In practice, there are two approaches to market segmentation: a priori and post hoc. An apriori technique predefines segments based on predetermined parameters such as age, gender, income, education, and so on, followed by profiling based on a variety of assessed variables (behavioral, psychographic, or benefit). The post-hoc technique of segmentation, on the other hand, identifies segments based on the relationship between the many measured variables. The shared feature of both techniques is that the measured variables decide the segmentation theme'. 


1. Explain how and which ML model (algorithm) helped you in 2nd Project.


In the 2nd Project, I utilized a combination of the k-means clustering algorithm and Principal Component Analysis (PCA) for the task. K-means is an unsupervised clustering algorithm that groups data points into clusters based on their similarity. It helped in segmenting the data into distinct groups based on certain features. PCA, on the other hand, is a dimensionality reduction technique that helps in reducing the complexity of the data by projecting it onto a lower-dimensional space while retaining the most important information. This combination of k-means and PCA enabled the identification of meaningful clusters within the data while reducing the noise and computational complexity. For the second dataset (dataset_2) I have used random classifier algorithm.


2. Elaborate on the final conclusion & insights gained from the research/analysis work. 

The final conclusion of the research/analysis work revealed several valuable insights:
Clear market segments emerged from the data, each representing a distinct group of customers with similar characteristics.
These segments could be characterized by specific attributes, such as purchasing behavior, demographics, or preferences.
By understanding these segments, targeted marketing strategies could be developed, tailoring products and services to better suit each segment's preferences.
Insights gained from examining the differences between segments could lead to product or service improvements, enhancing customer satisfaction.



3. How will you improve upon the Market Segmentation Project given additional time & some budget to purchase data? (in terms of Datasets collection - name what column points you will search for & what additional ML models you would like to try)

With additional time and budget, there are several ways to improve the Market Segmentation Project:
Dataset Enhancement: Acquire additional data sources that include more detailed customer information, potentially spanning demographics, transaction history, online behavior, etc.
Feature Enrichment: Collect data on customer interactions, feedback, and engagement to better capture their preferences and sentiments.
Geographical Data: Include geographical data to understand regional preferences and tailor strategies accordingly.
Social Media Data: Incorporate data from social media platforms to gain insights into customer discussions, sentiment analysis, and trends.
Additional ML Models: Experiment with more advanced techniques such as hierarchical clustering, Gaussian mixture models, or even more sophisticated models like random forests or neural networks to capture complex relationships.


4. What is the estimated Market Size for your Market Domain (non-segmented) in Numbers?

The estimated market size for electric vehicles (EVs) globally had been growing rapidly but can change significantly over time due to various factors such as government policies, technological advancements, consumer preferences, and market trends.

India Electric Vehicle Market size was valued USD 1.45 billion in 2021. The market size of India Electric Vehicle industry projected to grow from USD 3.21 billion in 2022 to USD 113.99 billion by 2029.

Furthermore, Indian automakers, such as Tata Motors, and Mahindra and Mahindra Ltd., have embarked upon aggressive efforts to add electrified vehicles to their product portfolio, which is expected to encourage Indian consumers to opt for electric vehicles. All these factors bode well for the growth of the electric vehicle market in India over the forecast period.


5. Name the top 4 Variables/features that can be used to create the most optimal Market Segments for your Market Domain.?

Range_Km (Range in Kilometers): The range an electric vehicle can cover on a single charge is a critical factor for potential buyers. Vehicles with longer ranges might appeal to customers who prioritize long-distance travel and reduced charging frequency.
PriceEuro (Price in Euros): The price of an electric vehicle significantly influences its market segment. Different price points cater to different customer segments, such as budget-conscious buyers, mid-range shoppers, and those looking for premium options.
Segment: The segment of a vehicle categorizes it based on its size, features, and intended use. Segmentation could include categories like compact, mid-size, SUV, luxury, etc. This variable helps target specific customer preferences and needs.
Efficiency_WhKm (Efficiency in Watt-hours per Kilometer): Efficiency represents how much energy an EV consumes to travel a certain distance. Vehicles with higher efficiency are more appealing to eco-conscious consumers and those who want to minimize their energy consumption.

The effectiveness of these variables for segmentation also depends on factors like market research, consumer preferences, and the competitive landscape. The goal is to identify meaningful segments that align with customer needs and preferences while also considering the attributes that set your products apart from the competition.






