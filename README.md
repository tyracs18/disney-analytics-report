# Enhancing the Disney Guest Experience with Analytics
#### Project Overview
Walt Disney World faces the challenge of maximizing guest satisfaction within limited time constraints. Many visitors only come once in their lifetime, making it critical to optimize their experience across attractions, dining, and entertainment.

Our project developed a three-model analytical framework to enhance the guest experience:
1. ARIMA Forecasting: Predicted attraction wait times based on historical data, weather, events, and crowd levels.
2. Clustering: Segmented guests into distinct personas (e.g., thrill-seekers, families with young children, food enthusiasts) using demographic and behavioral data.
3. Optimization: Generated tailored itineraries by integrating wait-time forecasts and guest cluster preferences, minimizing travel time and maximizing attraction coverage.

#### Key Contributions
- Forecasting Accuracy: Built an ARIMA model to predict ride wait times, enabling smarter labor allocation and real-time recommendations on the Disney app.
- Guest Segmentation: Applied clustering to identify meaningful guest personas, improving targeted marketing and personalized itinerary recommendations.
- Dynamic Optimization: Designed a linear programming model that adjusted itineraries in real-time based on ride downtimes, weather, and crowd patterns.
- Integrated Framework: Linked forecasting + clustering + optimization into a seamless system, balancing guest satisfaction with operational efficiency.

#### Impact & Insights
- Improved Guest Satisfaction: Guests could reduce time in line by 20–30% through dynamic wait-time forecasts and optimized attraction sequencing.
- Operational Efficiency: Disney could allocate staff more effectively based on forecasted peak periods, reducing bottlenecks.
- Revenue Growth: Segmented recommendations encouraged upsell opportunities (e.g., dining packages for foodies, merchandise for families).
- Scalability: Framework adaptable to holiday peaks, special events, and varying crowd behaviors.

#### Tools & Techniques
- Forecasting: ARIMA time-series modeling
= Clustering: K-means, demographic & behavioral features
- Optimization: Linear programming for itinerary planning
- Data Types: Historical wait times, weather, attendance, demographics, spending behavior
- Languages/Tools: Python (pandas, scikit-learn, statsmodels), R, Excel
