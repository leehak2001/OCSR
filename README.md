# PROJECT: Online Clothing Stores Ratings

## stage 1: Scraping the data.
__Main tools: Selenium, Webdriver, BeautifulSoup and re.__   

   - step 1 crawling_links: going through the websites's pages and taking the products's info pages's links
   - step 1.1 shopbop crawling: runing through all links of the shopbop website and creating a DF
   - step 1.2 avenue crawling: runing through all links of the avenue website and creating a DF

## stage 2: initial cleaning and combining data.
__Main tools: re, sklearn.__
   - step 2.1 shopbop cleaning: Treatment of Nan values, cleaning string anomalies, spliting list columns, deleting and adding columns to create the final df for the shopbop website.
   - step 2.2 avenue cleaning: Treatment of Nan values, cleaning string anomalies, spliting list columns, deleting and adding columns to create the final df for the shopbop website.
   - step 2.3 combining dfs: combining the two df and then, cleaning string anomalies, and organizing the columns that needed to be taken care of after the combination.

## stage 3: EDA & Visualization. 
__Main tools: pyplot, seaborn, wordcloud, re.__
   - step 3 vizualization

## stage 4: Final Cleaning and Machine Learning
__Main tools: sklearn, GridSearchCV.__
   - step 4.1 Final Cleaning: preparing the df for the model by aither taking down or label encoding string columns, as well as normalizing the price column. 
   - step 4.2 Machine Learning - Model: using, knn, decision tree, random forst, SVC, and naive byse, hyperparameter tuning and modifying the df to find the best model.

## stage 5: Conclusion
__Main tools: sklearn__
   - step 5 Conclusion: visualization of the final model and final conclusions. includes visualization of the confusion matrix, weight of features in the model and a random tree visualization from the random forst model.



___________________________________________________________________________
Accuracy on train data 0.845 Accuracy on test data 0.81 and f1_score: 0.76
