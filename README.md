# Swire-CC-Innovation-Demand-Forecasting
                                                      ![Swire CC- black cropped](https://github.com/RawaliMale/Swire-CC-Innovation-Demand-Forecasting/assets/139506913/c7df983f-3e55-42ad-ad62-651084bc0f62)




 
### Business Problem & Problem Objective:
Imagine a world where every product launch is a hit, with just the right amount manufactured. That's our mission with SWIRE-CC's innovative demand forecasting. Swire Coco-cola is facing problems regarding inventory control and production planning and hence the core issue we wanted to address in the project is the balancing act of production to prevent overage and underage, which have led to loss in the past. Swire is planning to launch seven innovative products to reduce the losses and maximize the profits.

Hence, our challenge is clear. Overproduction and underproduction are costly missteps we aim to avoid. The objectives we have set are to develop a robust machine learning model that use historic data, market trends and customer demographic information to predict future trends and patterns that helps in forecasting weekly demand, validating the model, and evaluating business risks. These are our navigation tools toward precise market predictions and optimal launch strategies.

### Group Solution:
Grounding our work are key assumptions, we've categorized regions to better understand market dynamics aggregating them into 6 different regionsand we decided to focus on unit sales, which offer a clearer demand picture than dollar sales alone. Also, we considered consecutive 13 best weeks of the year would be optimal, considering the market cost that involves in the product launch.

Since we don’t have exact replicas of the historic products that match our new product data, we have used a specific strategy. Our strategy harnesses consumer preferences across flavor, brand, category, and calories, funneling these through primary filters including flavor and manufacturer, and leaving room for regional specificity. At the core of our strategy is a robust modeling phase, where we scrutinize data and patterns, allowing us to refine our filters and enhance accuracy. This was the phase where our data transformed into decisions.

Considering the complexity of the problem, we tried to develop machine learning algorithms such as Prophet, Sarima, and Exponential smoothing for each question we sought to answer. Using different models gave us a deeper delve into the data stats and the predictions. Our evaluation criteria centered on error metrics helping us to know the effectiveness and accuracy of each model. This helped us to validate the performance of our models and then choose the winning model which is more reliable one for prediction. 

Our goal in choosing this strategy is to minimize waste and reduce excess inventory to save money and valuable resources. We are optimizing the likelihood of each launch's success by making certain that the right products are launched in the right markets at the right times considering consumer preferences, seasonal trends, and regional variations, driving efficiency, profitability, and optimized product launches.

### My contribution to the project:
Due to the complexity of the questions we need to answer, our project required planning and task distribution. We planned to do individual exploratory data analysis and modeling for around 2-3 questions each on the level of complexity of the question. I have been assigned to take up questions 3,4 and 5. I started with exploratory analysis with the data sets provided such as data cleaning, data manipulation and data preparation that is more appropriate to use for further analysis and modelling. I have considered the data manipulation steps such as handling the null values, variable transformations and changing the data set of customer demographics to pivoted customer x`by region mapping.

I further did Hypothesis Testing by considering various perspectives according to the question. I filtered out the data specific to the question asked for instance for Question 3, I funneled the data by the order Item as Kiwano, manufacturer as Swire CC, caloric segment as diet/light, category as Energy along side sorting the dates as our goal is to forecast the demand for consecutive 13 weeks. Similarly, for questions 4 and 5, region was one of the primary filters applied along with the other primary filters such as flavor, caloric segment. I have used powerBI to explore the data and the trends for different years across different regions and further drilled out by month and manufacture etc.

Apart from data exploration, I made significant contributions in developing forecasting models such as Sarima, Exponential smoothing, primarily using the prophet model for all the three questions as it performed better at the validation of the historic data and forecasting the future sales. Despite the variations in the model’s performance for different models, I prioritized rigorous evaluation, focusing on metrics like MAPE.

Throughout the project, I stayed flexible, adapting strategies to feedback, and actively contributed innovative ideas in team meetings for better project outcomes.

### Business Value/ Recommendations: 
Our modeling efforts have been successful in estimating sales, especially for the weeks after launch, and have yielded insightful information about future demand. Furthermore, we've realized how critical it is to use Social Media Analytics to collect client input so that we may continue to monitor their preferences and opinions. In addition, our sentimental analysis of two past products Starlight and Dream World has shed light on a variety of consumer tastes and lifestyles, offering invaluable information for customizing deals and sales strategies in the future.

By successfully analyzing and addressing all project questions, our team has delivered essential recommendations to Swire, empowering them to make informed decisions regarding their innovative product launches. Our solutions provide strategic information on the best times of year and locations, enabling Swire to make wise decisions that balance the act of production to prevent overage and underage costs resulting in maximized profits and minimal losses. Essentially our team’s approach to building a robust demand forecasting model drives superior outcomes for Swire's innovative product portfolio.

### Problems Encountered in the project:
As expected, the primary problem we encountered was dealing with the large data. Data extraction and data manipulation was quite a challenging task. It took us a couple of days to figure out the way to join the data sets or to import them. We tried different ways such as using google collab, parquet files but we ended up with data loss. We ended up using individual data sets for exploration and manipulating customer demographics by aggregating them into 6 different regions. Due to the large data sets we couldn’t work on the same data file simultaneously using google collab and hence additional time needed to spend while merging all the individual work done by teammates.

The second challenge we faced as a team was the assumption of 13 weeks. Initially we couldn’t figure out which 13 weeks of the year the demand forecast is expected. Consecutive 13 weeks of the year or any 13 weeks of the year which have high demand. Later we discovered that retail restocking is based on product performance following launch during our early conversations with Swire stakeholders. Swire additionally mentioned the possibility of brief launches, followed by restocking a few weeks later, although this looked unfeasible. As a result, when referring to the best 13 weeks of the year, we assume consecutive periods for launch and evaluation.

Other challenges we faced were evaluation and validation of the forecasting models as it needed an industry perspective. Taking suggestions from online sources such as YouTube, Udemy courses helped us in the process. 
### My learning through the journey:
As this was the very first time handling real time data, the journey of this project helped me understand the dynamics of the sales and data industry. I gained experience in managing large data sets, including strategies on filtering data and analyzing them according to the requirements. Through hands-on experience, I gained proficiency in various model validation techniques, particularly for time series data, ensuring the accuracy and reliability of our forecasts. Interacting with stakeholders deepened my understanding of business requirements and the importance of aligning our solutions with stakeholder expectations. Collaborating with the team helped me understand the significance of teamwork, dedication, and adaptability. The challenges we faced due to time constraints and stretching ourselves during the odd hours for completing a specific task gave me a better understanding of the time management and prioritization of the tasks.



