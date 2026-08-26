# ![Project banner](resources/banner.png)

## Car Price Analysis

The project aims to analyse the car market in the US to provide evidence for a business using a public dataset. Specifically for a Chinese car company called Geely Auto which aims to enter the U.S. market. They which to make an evidence-based series of decision to help the compete against European competition and directly with American brands. Their aim is to use measurable factors from sales data to identify the significant variables like engine size, horsepower, brand reputation, safety features, fuel efficiency, vehicle type, and additional technological advances to evaluate how it affects the price. The objective is to see if those factors differ in the US to China. The dataset will give us the which factors affect the car price in the US market. From the data we want to know which car features move in a predictable way with price and which ones do not.
With these results Geely can suggest strategic decision about product design and features which will help set an appropriate point that will drive price. They will then look at the price point information — they’ll use it to shape their entire U.S. market strategy as pricing data is one of the most powerful levers when entering a mature, competitive market like the U.S. Geely then position themselves against competitors with precision to avoid assumptions and make decisions based on real American market behaviour.

Data set content.
For this project the data source Kaggle and there are just 205 cars. The dataset tells us details about the car, from its size, engine specification, fuel, power, aspiration (turbo) efficiency and price. Limitations is we’re not told where in the US its sold, nor by who. We can assume they’re all new cars without mileage and randomly sourced from various states around the US. This potentially limits the reliability of the conclusions for example location bias due to climate or state wealth.

Business requirements and goals
They want to finds positive coefficients in any of the data they’ve obtained to tell them which features of cars American buyers are willing to pay more for. So, aim is to identify which features are worth investing in for their export market and to design vehicles that match American preferences to boost sales.
User Stories
CEO of Geely Auto, wants to know the main price drivers to align price of vehicle line to compete with European rivals.
Marketing manager, wants to know which features to advertise and which ones to avoid, he might be coming from a background where those features differ.
Production manager, he wants to see cost effective it would be to make adjustments to cars and remain cost-effective
Data Analysts, using the result of the lowest Root Mean Squared Error wants to work with those factors in a model that best predicts the price so he can hit an accurate estimation what it should be.

What you are looking for. Questions. Which answer is using Analytics to support Making an evidence based business decision
Hypotheses: what do I think will happen why? How? What are the targets?

Project Plan. What is the plan to reach the business requirements and answer the questions?
Obtain data, look at structure and initial exploratory checks.
Data Cleaning Process. We will get an overview so we understand the fields.
• Check for duplicates, identify and remove duplicate rows. (context aware)
• Handle Missing data. (strategy to resolve and options)
• Detect and Manage Outliers
• Handling data anomalies.
Data processing. Looking at categorical columns, scaling back and splitting data.
Initial Visualization. Initial plots, comparing price with features, looking for correlation trends.
Interpretation and further focus area of interest.
Chosen Analysis technique and libraries will be a Model selection (Linear Regression), library setup (Pandas, Scikit-Learn).
Analysis through interpretation and prediction Training the regression model, calculating RMSE and R²

Future consideration. Translating the finding to a marketing strategy to identify the scope and domain.

Credits

Content taken from
Acknowledgements
