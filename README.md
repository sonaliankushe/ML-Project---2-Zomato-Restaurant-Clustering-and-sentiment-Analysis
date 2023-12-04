# ML-Project---2-Zomato-Restaurant-Clustering-and-sentiment-Analysis
Problem Statement and Project Description
Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities. The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and make some useful conclusions in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is visualized as it becomes easy to analyze data at instant. The Analysis also solves some of the business cases that can directly help the customers finding the Best restaurant in their locality and for the company to grow up and work on the fields they are currently lagging in. This could help in clustering the restaurants into segments. Also the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis Data could be used for sentiment analysis. Also the metadata of reviewers can be used for identifying the critics in the industry.
India is well-known for its unique multi-food cuisine, which is offered in a huge number of restaurants and hotel resorts and symbolizes unity in variety. In India, the restaurant industry is changing rapidly. More People are appealing to the concept of eating restaurant meals, whether they dine outside or have food delivered to their homes. The increasing number of restaurants in every Indian state has encouraged an analysis of the information to gain some insights, noteworthy facts, and statistics about the Indian food sector.
As a result, the purpose of this study is to analyze Zomato restaurant data in Hyderabad. Zomato is a restaurant aggregator and food delivery service based in India. With the use of unsupervised and supervised machine learning algorithms, the work here clusters restaurants into distinct segments and evaluates the sentiments in customer reviews. The analysis also resolves several business cases that can directly assist customers in locating the best restaurant in their area, as well as the company's growth and development in areas where it is currently underperforming.
This project contains an executable file, a technical document and a presentation
Attribute Information
Use this dataset for clustering part
1.Name : Name of Restaurants
2.Links : URL Links of Restaurants
3.Cost : Per person estimated Cost of dining
4.Collection : Tagging of Restaurants w.r.t. Zomato categories
5.Cuisines : Cuisines served by Restaurants
6.Timings : Restaurant Timings
Zomato Restaurant reviews
Merge this dataset with Names and Matadata and then use for sentiment analysis part
1.Restaurant : Name of the Restaurant
2.Reviewer : Name of the Reviewer
3.Review : Review Text
4.Rating : Rating Provided by Reviewer
5.MetaData : Reviewer Metadata - No. of Reviews and followers
6.Time: Date and Time of Review
7.Pictures : No. of pictures posted with review
Data Cleaning and Preprocessing
Feature Engineering
Feature engineering is the process of selecting, manipulating, and transforming raw data into meaningful numerical features that can be used by machine learning algorithms.
Zomato Restaurant names and Metadata
First, the restaurants dataset has columns such as Links, Cuisine, and Timings which aren't directly interpretable. The location of the restaurant can be extracted by the Links column. Cuisines can be clubbed and categorized into a few categories and a total number of cuisines served by a particular restaurant. Timings can be categorized into three categories to make analysis a little simpler.
Exploratory Data Analysis
Exploratory data analysis is a crucial part of data analysis. It involves exploring and analyzing the dataset given to find patterns, trends and conclusions to make better decisions related to the data, often using statistical graphics and other data visualization tools to summarize the results. Python libraries like pandas are used to explore the data and matplotlib and seaborn to visualize it.
Some important aspects to include in the project are as follows:
Best restaurants in the city
The Most Popular Cuisines in Hyderabad
Restaurants and their Costs
Cost-Benefit Analysis
Hypotheses Generation on visualized data for Clustering

Cost-Benefit Analysis
Whenever we start a business project or make a business decision we need to analyze whether the decision will be worthwhile. A Cost-Benefit Analysis is a process of analyzing the worth of a decision by estimating the costs incurred in implementing that decision and comparing them with the benefits of that decision. If the projected benefits outweigh the costs, we'll be making money out of that decision and if not, it's important to strategize a better plan.
Zomato is an Indian restaurant search and an online food delivery service. Zomato focuses on online food ordering, restaurant reservations, and loyalty programs. The target customers for the company are restaurant chains that want to reach a larger audience and application users who just want to try out local restaurants and various cuisines. Here is a simple cost-benefit analysis that can be carried out on the basis of the little information we can assume.
Costs
When tallying costs, beginning with direct costs, which include expenses directly related to the production or development of a product or service (or the implementation of a project or business decision) which is in the case of Zomato is primarily the mobile application. Maintaining the application, strategizing plans, including the restaurants, marketing, food delivering partners and customer support needs a huge team to work on. The salaries of the employees would be a direct cost.
Other indirect costs include utilities, rent, partners, advertisers, etc.
There are some other costs that are difficult to measure such as negative reviews on the platform which leads to people avoiding the application altogether, bad presence on social media, etc.
Benefits
The major source of Revenue is Advertising. More and more restaurants want to promote themselves on the Zomato feed in order to gain attention and visibility from a large section of Zomato subscribers and customer base.
Through the food delivery service, Zomato charges a commission to the restaurants on the basis of orders. The company earns through restaurants that pay a commission for each delivery, which is then split among the delivery partners and the company. However, online food delivery only contributes a low percentage of income compared to other revenue streams because of the huge competition and the need to provide deep discounts, etc.
Comparison
The data that we have consists of per-person cost, cuisines available at the restaurant, and an average rating of the restaurant. If a restaurant isn't performing well in terms of rating and has a high per-person cost and a low number of popular cuisines, this is going to be a problem for Zomato. Since negative reviews would be an intangible cost to the company and with that the company will start to lose daily application users. The application users are an asset to the company, Zomato gets advertising by different restaurants because of the large audience they have.
All in all, it is important to separate out the restaurants that Zomato needs to work on in order to improve its overall customer experience and if improvement strategies don't work out, they need to delist those restaurants themselves.
Hypotheses Generation on visualized data for Clustering
Clustering is done on the basis of similarities between the data points. The similarities are understood by how closely distanced these points are. The following are some hypotheses that can be generated by finding some similarities in the visualized data:
Restaurants with similar kinds of ratings can be clustered together. Ratings are done by people on the basis of food quality, service, packaging among other things.
Restaurants with high ratings would also probably be expensive and would be having a similar pricing strategy as well. They can be clustered according to the costs.
Restaurants having some of the most popular cuisines can be clustered together and restaurants with exotic cuisines such as Indonesian, Mexican, Japanese, etc can be clustered as they are really low in number.

Sentiment Analysis
In the business problem, predicting the negative sentiments correctly is really important but is more important for the models to reduce the number of false positives. False positives indicate that the reviews were actually negative but they were categorized as positive and this will lead to missing a complaint to work on.
Even though the number of false negatives is higher in the case of Logistic Regression than Random Forest, it is performing better in terms of reducing False positives. This indicates that Logistic Regression is penalizing False positives more just as we want.




