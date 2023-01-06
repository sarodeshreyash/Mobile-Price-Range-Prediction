# Mobile-Price-Range-Prediction
Machine learning classification project
Mobile-Price-Range-Prediction
 
# Problem Statement
There are many things we consider before buying a mobile as we used our mobile for various purpose like connecting with our family & Office Colleagues, playing games, taking a photo’s to keep our memory alive. So this such specifications such as RAM, internal memory, Wi-Fi, 3G/4G connectivity etc. plays important role to buy a mobile. To analysis of this important factor from time to time and come up with the best setoff specifications and price ranges so that people will buy the mobile. Hence through the various ML modules we will help the company to estimate the price of mobiles according to feature so the maximum amount of sell will be possible.

# Data Description
We have been provided with the dataset containing the 2000 rows and 21 features
• Battery power - Total energy a battery can store in one time measured in mAh
• Blue - Has Bluetooth or not
• Clock_speed -speed at which microprocessor executes instructions
• Dual_sim - Has dual sim support or not
• Fc - Front Camera mega pixels
• Four_g - Has 4G or not
• Int_memory - Internal Memory in Gigabytes
• M_dep - Mobile Depth in cm
• Mobile_wt - Weight of mobile phone
• N_cores - Number of cores of processor
• Pc - Primary Camera mega pixels
• Px_height - Pixel Resolution Height
• Px_width - Pixel Resolution Width
• Ram - Random Access Memory in Mega Bytes
• Sc_h - Screen Height of mobile in cm
• Sc_w - Screen Width of mobile in cm
• Talk_time - longest time that a single battery charge will last when you are
• Three_g - Has 3G or not
• Touch_screen - Has touch screen or not
• Wifi - Has wifi or not
• Price_range - This is the target variable with value of 0(low cost), 1(medium cost),2(high cost) and 3(very high cost).



# Data Processing
Understanding and cleaning the data

# Data Exploration
Analyze the data through visualization

# Model Performed
• Decision Tree Classifier
• Random Forest Classifier
• K Nearest Neighbor
• Gradient Boosting Classifier
• XGB Classifier
• Support Vector Machine


# Conclusion
**EDA**
*   Data Wrangling and Data Visualization has provided the best idea about the features involved in the datset.

*   We are fortunate that the dataset was almost a cleaned one with no null values present or duplicate records found, it helped in maintaining the correct pace.

*   Most of the categorical features had a similar distribution or count except the feature '3G'. There were very few records for mobile phones which doesn't support 3G. 

*   While determining the distribution of Categorical features with respect to the taget variable finding states that all the categorical variables namely 'dual_sim', 'wifi', 'blue', 'touch_screen', 'three_g', 'four_g' have a similar count of data for each classes which ranges mostly in between 230 -260(almost)except the variable 'three_g'.In 'three_g' there are very few number of mobiles which doesn't support 3G across all the price ranges.And the number of mobile phones that supports 3G(comparing to mobiles not having 3G) ranges more than 350.
* *By increasing the size of ram , price increase alot.*
* *Most number of low cost mobiles, has battery power 750(mAh). Most expensive mobiles have better batteries i.e. 1500-2000(mah)*
* *Heviest mobiles have low cost**
* *Most of mobiles in all price range, has 0.5 clock speed.*
* *Very high cost mobiles have bigger height and width in cm*
* *mobiles that don't have front camera have medium price*
* *Most of mobiles in all price range, has front camera with 2 mega pixel.*
* *Most of mobiles in all price range, has 4 cm width.*



**ML Classification**

*   Based on to our main objective to predict the Mobile Price Range. **Support Vector Machine** is the best performing model, out off all the other models used  namely Decision tree, Gradient Boosting, Knn, Random Forest, XGBoost.

*   Knn model is the worst performing models for our dataset
