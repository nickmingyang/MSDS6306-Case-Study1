# MSDS6306-Case-Study1
**Author: Babatunde John Olanipekun, Yvan Sojdehei and Mingyang Nick YU**
### Purpose: This is a team case study aiming at exploring/analyzing dataset (Beers.csv and Breweries.csv) provided by CEO and CFO of Budweiser, answer specific questions and beyond
# Case-Study1 structure: 
#### Datasets(Beers.csv,Breweries.csv) -- if were to run result need to adjust read.csv location accordingly
#### Dataset(uscities.csv) -- provide city locations(latitude and longitude) in order to produce informative map plots
#### Dataset(states_coord.csv) -- provide state center coordinates in order to print state label on maps
#### Case_Study_1.RMD: This is a R markdown file including description, analysis of each question, r code to accomplish our analysis and conclusion
#### Case_Study_1.html: This is a knit file generated from RMD file above, a nicer overall report including the graphics from RMD file
#### PPTX: This is our presentation deck, to summarize our findings to present to CEO and CFO of Budweiser
#### In order to successfully run the RMD file, you need to download corresponding libraries that are used in the RMD file
#### This project can be found under github link: https://github.com/nickmingyang/MSDS6306-Case-Study1
#### YouTube Presentation by Nick YU: https://www.youtube.com/watch?v=kRLRgAZHtS4
#### YouTube Presentation by Yvan Sojdehei: https://youtu.be/ktNJocfN7bU
#### YouTube Presentation by John Olanipekun:https://www.youtube.com/watch?v=gfhTaR_Ttek

### Conclusion:

#### We received datasets that contain beers and breweries.We are trying to discover any relationship between Alcohol by volume(ABV) and International Bitterness(IBU). Scatter plot shows a positive but weak linear relationship between ABV and IBU. We used such relationship between ABV and IBU to classify types of Ales into Indian Pale Ale or other types of Ales. The accuracy rate of our KNN model is pretty good at 80%, we can correctly predicting Indian Pale Ales at 78%, and correctly predicting other types of Ales at 81%. We obtain similar results from Naive Bayes model, except correctly predicting Indian Pale Ales at 68%. However, depending on what the customer is looking for, Naive Bayes model can be more efficient.

#### We obtained density plots of all beers produced at facilities near cities. We were then able to go deeper into the dataset and show facilities of any kind of beer, such as Ales. This is a great asset management tool, and gives us overview of which kind of beer are more prevalent facilities across the country. It gives us leads to dig deeper into areas and find out why? Cost(Need sales data)? Resources(Need agriculture data)? Popularity(Need more research)?
