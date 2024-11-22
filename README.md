# Python
**Sample Python Scripts**

This is a folder with various files needed to create the data source for this work in progress Tableau Dashboard: 
https://public.tableau.com/app/profile/colin.mcduffie5149/viz/WebRetailerForecastingModel/MainDB

1) Use the "Create Web Traffic Dummy Data.ipynb" file to create your own random dummy data to practice on. If you have your own data from Google Analytics etc. Then you can skip this step.
2) Open and run the "Beginner Dummy Web Revenue Forecast.ipynb" file to explore your data and run your first ML model. I added the script for a Random Forest Model but feel free to use Linear Regression or any model you're curious about.
3) Decide which features you want to keep and which ones to omit. Rerun the workflow until you get a desired R2.
4) You are now ready to move onto the "Advanced Dummy Web Forecast.ipynb" script. This is much more complex but shows all the necessary steps needed to create the final dataset. 


For those using your own data, please follow the schema. Feel free to replace the Google, Facebook and Direct features with your desired platform (ie Pinterest, TikTok, Organic etc). 

 #   Column                      Dtype  
---  ------                        --------------  -----  
 0   Date                          1096 non-null   object 
 
 1   Google_Desktop_Visits         1096 non-null   int64 
 
 2   Google_Desktop_Conversions    1096 non-null   int64 
 
 3   Google_Mobile_Visits          1096 non-null   int64 
 
 4   Google_Mobile_Conversions     1096 non-null   int64  
 
 5   Google_Spend                  1096 non-null   float64
 
 6   Google_Revenue                1096 non-null   int64  
 
 7   Google_ROAS                   1096 non-null   float64
 
 8   Facebook_Desktop_Visits       1096 non-null   int64  
 
 9   Facebook_Desktop_Conversions  1096 non-null   int64  
 
 10  Facebook_Mobile_Visits        1096 non-null   int64 
 
 11  Facebook_Mobile_Conversions   1096 non-null   int64  
 
 12  Facebook_Spend                1096 non-null   float64
 
 13  Facebook_Revenue              1096 non-null   int64  
 
 14  Facebook_ROAS                 1096 non-null   float64
 
 15  Direct_Desktop_Visits         1096 non-null   int64  
 
 16  Direct_Desktop_Conversions    1096 non-null   int64  
 
 17  Direct_Mobile_Visits          1096 non-null   int64  
 
 18  Direct_Mobile_Conversions     1096 non-null   int64 
 
 19  Direct_Spend                  1096 non-null   float64
 
 20  Direct_Revenue                1096 non-null   int64  
 
 21  Direct_ROAS                   1096 non-null   float64
 
 22  Bounce_Rate                   1096 non-null   float64
 
 23  Avg_Session_Duration          1096 non-null   float64
 
 24  Pages_Per_Session             1096 non-null   float64
 
 25  Conversion_Rate               1096 non-null   float64
 
 26  Total_Conversions             1096 non-null   int64  
 
 27  Total_Revenue                 1096 non-null   int64  
 
 28  Total_Spend                   1096 non-null   float64
 
 29  Total_Profit                  1096 non-null   float64
 
 30  Total_ROAS                    1096 non-null   float64

