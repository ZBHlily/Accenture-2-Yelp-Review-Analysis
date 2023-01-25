![](https://github.com/ZBHlily/Accenture-2-Yelp-Review-Analysis/blob/main/AI%20Studio%20Final%20Project%20Presentation%20.jpg)

# Accenture #2 - Yelp Review Analysis

**MEMBERS:** Weijia Song, Lily Liang, Daphne Tang, Stephanie Moreira

----

### **CONTEXT:**

A restaurant group approaches Accenture as they need help identifying certain attributes which contribute to the success or failure of a restaurant.


----

### **DATASET DESCRIPTION:**

The datasets will be pulled from Yelp's website which provides files on restaurant data (including reviews, pictures, and restaurant details.)These datasets include numerical data, text descriptions, and images. There are additional Yelp datasets available on Kaggle.
![](https://github.com/ZBHlily/Accenture-2-Yelp-Review-Analysis/blob/main/yelp_dataset.png)

----

### **CHALLENGE:**

Propose an NLP analysis-oriented ML challenge to assess open-source Yelp data which contains user reviews, business information attributes, and photos to understand how restaurant customers interact with restaurants and what will build a good customer experience using Dataiku.


----

### **APPROACH:**

Using the business attributes and/or text from reviews from the Yelp dataset can be used to create a supervised model that predicts overall
sentiment. By building a supervised model, the participants can identify which words are connected to a positive customer interaction. Example libraries such as NLTK, Sci-kit Learn, Tensorflow, Keras, Pytorch, etc can be considered for the analysis; although, user is not limited by the aforementioned list. In this challenge, students will gain experience with NLP, Sentiment Analysis, Machine Learning and/or deep learning to approach a business problem. The output of the analysis should include a robust ML model, an end-to-end description of the data science process, and a comprehensive post-model report which includes metrics, and illustrates which features (words) most contributed to a positive or negative sentiment.

1. **Sentiment Analysis** 
    - Use sentiment analysis models to learn the traits of positive/negative reviews

2. **Topic Modeling** 
    - Perform topic modeling on our datasets to find top “features” that are most relevant in positive/negative reviews
    - Used: Python Libraries(Numpy, Pandas, Scikit-learn)

3. **Analyze Results**
    - Determine top features (definition) that lead to positive/negative sentiments help restaurant to find top features
    - Advised to use segmentation to split up the reviews into dishes and service, and clustering

![](https://github.com/ZBHlily/Accenture-2-Yelp-Review-Analysis/blob/main/topic_modeling_cafe.png)

----

### **SUMMARY**
Determine what makes a restaurant successfully depending on its' dishes, recipe inspiration, service, environment, and occasion. The restaurants were broken up into five different categories such as seafood, italian, cafe, asian, and nightlife. 
1. **Cafe**
    - Top Keywords from Topic Modeling
       - Positive: homemade, creamy, fresh, breakfast, lunch, quickly, grab, coffee, tea, drink, local, friendly, selection, warm, tasty, price, atmosphere
       - Negative: wrong, order, wanted, cold, stale, flaky, bland, portion, flavor, quality, rude, long, waiting line, service, wait, lines, priced, pricey  
    - Insights: 
       - Occasion: Breakfast & Lunch
       - Food: More Flavors, Homemade, and creamy foods
       - Environment: Friendly atmosphere, local; location at downtown, chinatown
       - Service: Correct order and ready quickly 

2. **Seafood**
    - Top Keywords from Topic Modeling
       - Positive: fresh, portion, big, wait, quickly, dinner, nightisland, beach, atmosphere, bar 
       - Negative: soggy, grease, tasteless, bland, sweet, salty, cold,  waiter, rude, hungry, waited, slow, price
    - Insights: 
       - Occasion: Dinner & Night
       - Food: Fresh food, Big portions
       - Environment: Nice and clean atmosphere, Have a bar, Location at island or beach 
       - Service: Friendly service, Quick wait time


For more information, refer to the presentation: https://docs.google.com/presentation/d/1Y6DlU65_q1yw9BIN7BShPtX1pxM0DBrv06_p0HQJ2u4/edit?usp=sharing


----
### **NEXT STEPS**
1. Regions
    - Filter out specific regions
       -  For all 50 states or even cities since each of them have different tastes and preferences
2. Cuisines
    - Add more categories of cuisine
       -  More dish options like having a Hawaiian cuisine or korean cuisine
3. Pipeline
    - Deploy Pipeline
       -  New business owners can use our insights to see what customers are looking for in that particular country/cuisine 
