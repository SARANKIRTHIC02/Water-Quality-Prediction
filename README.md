# Water-Quality-Prediction
# 1. Problem Statement 
The problem statement is due to Inadequate lab facilities are often cited as a challenge or limitation for the general public and small scale business who are not able to target their specific locality to test the quality of water they use at their homes. Small scale businessmen have to wait long for municipality water checks. They need fast and reliable results .Labs can become the weak link in the water quality assessment chain because they are vulnerable on several levels like technical,human resource and time consuming.

# 2. Market/Customer/Business need Assessment 
A careful judgment about the need for water quality testing is essential. Water quality testing can be an expensive and difficult task if it is done properly. You should review the need for water quality testing within the context of your project and its objectives. When determining if and how much water quality testing to conduct, the following factors should be considered are Budget, Capacity of the staff to conduct testing, Availability of testing equipment, and consumable items.

There are alternative ways to assess water quality, such as conducting 
user surveys and sanitary inspections. including: 

 Quantity of treated water 
 User Satisfaction 
 Robustness 
 Ease of maintenance and operation 
 Affordability 
 Availability 
 User perception of taste, smell, and color.


However, testing is necessary if you need to assess a treatment technology for its effectiveness in removing contaminants from the drinking water. There are other situations that may also require some water quality testing, such as: 

End-user or community request
Water supplier request 
Government verification of a treatment technology 
Monitoring compliance with standards or guidelines 
Research purposes 
# 3. Target Specification 
The proposed system/service will provide the Water distributors with some techniques so that their sales boost up and they no longer have to go through an economic crisis. It will suggest them to group certain localities together, based on the analysis performed by the algorithm, so that the distributors earn more profit from these localities grouped together. Also, applying certain discount strategies on such grouped localities will also increase the sales as required. As far as the local water refilers are concerned, the analysis aims at suggesting to them the water quality in a certain area, which they can eventually consider for business and hence, increase their sales as well. 
# 4. External Search 
The sources I have used as reference for analyzing the need of such a system for local businesses and how E-commerce giants have been using the technique to boost up online sales, have mentioned below : 
● Understanding Customer Behaviour 
● How water distributors can be benefited 
● Water purity detection explained
● Increasing Sales and Improving ROI 
● A study on Understanding Changing Trends of Customer Behaviour and hence the Market 
# 4.1 Benchmarking alternate products

As such there isn't any direct competition for this product at this point of the time in the market we provide various feathers which many companies/products does not provide cumulatively the competitors price cap is also bit high when compared to ours and getting verified/certified water supplier would mean that the consumers would be more assured to be safe from contaminants when they purchase water from the certain supplier who has these certifications. Most of the testing and analysis is carried out at designated labs, but our product does give an option for a hands-on kit by which they can evaluate the results rapidly and consumers would be more involved when it comes to getting results of the water test conducted. Our product will predict the result from the previous history of water samples that will help the household consumer to change their RO filters when the water they consume turns out to be contaminated it will provide a warning message.

# 4.2 Applicable Patents 
● Patent 1 - Smart Water Monitoring System for Real-Time Water Quality and Usage Monitoring’
● Patent 2 - Enhanced Water purity detection 
There are a lot of patents that can be looked upon, but since these two relate the most to the application mentioned above,I have mentioned them. 
The first patent describes in detail the water purity detection and how it has been used for generating purity in terms of different parameters based on the customer inputs identified from the applicable dataset, according to predetermined attributes.
The second patent describes an enhanced model for Water purity detection. This model can generate a list of parameters(grouped together) based on historical data, which are causal and predictive,and the output can then be fed as input to another output generator which generates the final product groups, along with a score that characterizes the likelihood of the water sample for the predicted group. 
These two will be significantly considered while developing and implementing a similar system for small scale businesses. 
# 4.3 Applicable Constraints 
● Sample Collection from water distributors
● Continuous data collection and maintenance 
● Lack of technical knowledge for the user(vendors) 
● Convincing the shopkeepers to trust the results from the model. 
# 4.4 Applicable Regulations 
● Data protection and privacy regulations(Customers) 
● Govt Regulations for small businesses 
● Employment Laws 
● Antitrust Regulations 
● Regulations against false advertising 

# 4.5 Approach

1) We load the dataset from Kaggle which has a large amount of structured data and initially filter out the category containing the “Warning” message by using simplefilter() .

2) Now the dataset is loaded into a data frame and we will find out the mean for Solid particles with a concentration above 50% (including) as it is the maximum threshold allowance by the scientist and government officials.

3) Discard all the NULL values present in any column of the dataset which was uploaded before from the dataset.

4) Since there is very little correlation between the chemical compounds, Therefore we adjust the negative values by using skew _ correct() to rotate the values of data.

5) The filtered dataset is now trained on K-Means algorithm Classification() with the “KNN” predictor to perform SMOTE so that the K-Means algorithm will not ignore the parameters.

6) Now we display the accuracy scores.

# 4.6 Benefits

There are many benefits of this project some of them are:-
Easy to use 
Portable and self-contained  
Rapid results  
Does not require a high level of training  
End users are able to participate in the testing process 
Less expensive than laboratory testing
High level of precision and accuracy 
High level of quality assurance 
More consistent results 
More samples can be processed in a shorter time.
Track record of previous results
Certification of water quality
Prediction based upon history

# 4.7 Customer Segment
B2B Market
Companies in the business of delivery and supply of water.
Companies in the business of installing purifiers in safe water prone areas
B2C Market
Customers need door services for testing of water.

# 4.8 Customer Relationship
Product Website: Our product website will contain customer review forms where they can leave their thoughts and also will be able to give us feedback on what we could do better.

Email/Phone: We will also be sending emails to customers through their contacts from the survey we conducted and creating awareness about our product.

Customers Department: Our customer service department will be responsible for handling customer complaints and other needs of the customer. 
 


# 4.9 Channels 

Product Website

Local dealership and contracts.

Direct to customers

# 5. Business Opportunity 
A Business opportunity evaluation is the method of combining market research and client information to track growth potential in a certain market or business area, as well as strategizing to accomplish that growth.
Market research is critical to a business's success.
A solid company plan examines and evaluates customer demographics, purchasing behaviors, and willingness to accept new goods and services.
The first step is to comprehend the market.
As part of this method, a number of questions must be asked and, more importantly, answered.
If we completely answer the following questions, we will have a better grasp of our market.
# 6. Final Product Prototype 
The final product is a service that provides small businesses with detailed information on what is the water quality of the locality and other similar useful insights into how to increase the sales of their business. 
The service implements the water purity analysis, i.e Machine learning (LDA) technique on the dataset and water sample collected from vendors
Each sample will have a group of parameters like water sample analysis with different parameters of water. 
These are then analyzed to identify the niche for the business.
The Appropriate machine learning Algorithm will be used.
Generating results is the computationally expensive step, which can be improved using data preprocessing, error reduction, accuracy increasing, sampling and different algorithms. 

# 7. Conclusion 
More and more organizations are discovering ways to find their perfect customer who are in need of the service or product to gain useful insights into associations and hidden relationships. But this extension for small businesses is a great opportunity to improve sales and help these businesses grow. 
I have hence proposed the application of this technique for small businesses. This isn't a complete product. To deliver a complete product we have to do a web page for the ML algorithm.

