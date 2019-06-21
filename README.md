# Seattle-Data-Analysis

## Blogpost
https://medium.com/@rikus.fourie/in-search-of-airbnbs-success-ff16edbb2555?postPublishedType=initial

## File contents

    .
    ├── images                                     #Static plotly figures. See notebook for description
        ├── bin25.png
        ├── bin50.png
        ├── bin75.png
        ├── pandr_type.png
        ├── pricevsapart.png
        ├── property.png
        └── property.png
    ├── seattle                                     #Datasets
        ├── calendar.csv                            #Calander listings
        ├── listings.csv                            #Listings details
        └── reviews.csv                             #Reviews details
    ├── SeattleAnalysis.html                        #Html version of workspace
    ├── SeattleAnalysis.ipynb                       #Workspace where all analysis where completed
    ├── LICENSE
    └── README.md

## Libraries used
The notebook was run on Python 3.6.3, please ensure your version is at or above this version level to run.
- Pandas
- Numpy
- Matplotlib
- Plotly
- Sklearn
- statsmodels
- scipy

## Project Overview
The main focus of this project was to analyze Airbnb Seattle's data to try and find a reason for their success. I asked 3 main questions in order to find the answer to my main question:
- Does the amount of available listings affect the price?
- What is the most common type of Airbnb living situation?
- What is the most listed price range?

## Process followed with each question:
I followed the crisp-dm methodology to answer each of these questions as well as to answer the overall question. 

The crisp-dm process is as follows:
- Business understanding
- Data understanding
- Data preparation
- Modeling
- Evaluation
- Deployment

## Summary of results
The first question I asked was about how the availability was affecting the price. To my surprise, I couldn't find any significant link between price and availability. To me, this might be an indication that Airbnb could have an oversupply of listings and therefore a shortage won't happen at the moment. For Airbnb, this is a great thing since it means that they will always be able to help the end user, and since they don’t own the living quarters themselves they won’t take too much know when demand is low.

The second I asked had to do with the common type of living situation. I found out that people would mostly live in apartments and houses where the majority of people will live on their own or in a private room. For me, the fact that houses and apartments were so highly used indicates that Airbnb’s users prefer a different approach to living compared to the traditional hotel. This might also be another good reason why Airbnb does so well.

The third and final question was focussed on price ranges. To me, this is probably one of the most important points in Airbnb's success. As we saw on the analysis of price ranges, users tend to go more for the lower end of the spectrum in terms of pricing. Since Airbnb’s main competitor is hotels, I believe pricing plays a major role in their success.

## Conclusion
In this project, I explored some interesting stats and figures and answered 3 of the main questions I had about Airbnb. The overall focus of this blog post was to find out why Airbnb was doing so good. I believe that through their low price rates, the ability to stay in a house or apartment rather than a small hotel room and the fact that there are so many options to choose from all really plays a big role in Airbnb’s success.

## Acknowledgements
I would like to thank Airbnb for graciously supplying this dataset for analysis and for Udacity helping me learn the art of analysis.

## References
- https://stackoverflow.com/questions/27928275/find-p-value-significance-in-scikit-learn-linearregression?answertab=active#tab-top
- https://www.sv-europe.com/crisp-dm-methodology/
- http://insideairbnb.com/seattle/?neighbourhood=South%20Delridge&filterEntireHomes=false&filterHighlyAvailable=false&filterRecentReviews=false&filterMultiListings=false
