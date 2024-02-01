# Project-3-Fastfood Topic: Nutritional Content of Fast Food

## An overview of the project and its purpose
Our project provides the nutritional value of food sold at eight major chain fast food restaurants located in Minnesota, specifically at locations within the [Twin Cities, Minnesota.](https://en.wikipedia.org/wiki/Minneapolis%E2%80%93Saint_Paul) This will allow users to analyze/compare several nutritional content:
* calories
* protein
* sodium
* carbohydrates
* fat
* sugar
* cholesterol
* fiber 

We have created visualizations to display the nutritional content of specific foods and allow users to compare food items. We also created an interactive quiz to help visitors make informed choices when ordering some of America's favorite fast foods.
  
## Instructions on how to use and interact with the project
- ![image](https://github.com/Chud-rf/Project-3-Fastfood/assets/140283164/93d69e45-40fd-4410-8f8e-5f92bebc6458)


## At least one paragraph summarizing efforts for ethical considerations made in the project
Ethical considerations made for this project: we are assuming fast food is unhealthy. We chose to not utilize web scraping for pricing data since fast food companies as well as websites with pricing data specifically stated we could not scrape data. The source of the dataset is Kaggle.com and the Fastfood Nutrition dataset references this license: and the Top 50 Fast-Food Chains in the USA dataset license is created from QSR Magazine. 
After researching the restaurants’ Terms of Service posted on their websites, we decided not to post any company logos on our project. Doing so would require written consent from many of the chains, since a company’s logo and marks are viewed as proprietary material. Burger King’s website was the strictest, listing out several types of prohibited content and activities, not limited to spidering, scraping, harvesting, reverse engineering, deciphering or attempting to circumvent any software that’s part of the Services. All chains referenced the Children’s Online Privacy Protection Act of 1998.

## References for the data source(s):
* pygwalker references:

* https://github.com/Kanaries/pygwalker
* https://www.youtube.com/watch?v=Ynt7Etci1KU
* https://stackoverflow.com/questions/36351109/ipython-notebook-ipywidgets-does-not-show

* Flask reference:
*  https://www.digitalocean.com/community/tutorials/how-to-use-an-sqlite-database-in-a-flask-application

* Dataset:
*  https://www.kaggle.com/datasets/ulrikthygepedersen/fastfood-nutrition [Which fast food products are worst for you?]
*  https://www.kaggle.com/datasets/iamsouravbanerjee/top-50-fastfood-chains-in-usa [USA's Culinary Landscape: A Deep Dive into the Top 50 Fast-Food Chains (2021)]

## References for any code used that is not your own
- Basic Quiz Code
     - https://medium.com/@codepicker57/building-an-interactive-quiz-with-html-css-and-javascript-efe9bd8129e2
- Flask app route code - assistance from ChatGPT
- Map Code
     - Help to set the background color of the legend [here](https://codepen.io/haakseth/pen/KQbjdO). 
     - Code found here for fit bounds in leaflet found [here](https://jeffreymorgan.io/articles/how-to-center-a-leaflet-map-on-a-marker/).
     - Support setting up the legend found [here](https://codepen.io/haakseth/pen/KQbjdO) and html color identification found [here](https://htmlcolorcodes.com/).
     - Code for word-wrap in legend found [here](https://stackoverflow.com/questions/3587390/how-can-i-make-text-appear-on-next-line-instead-of-overflowing)



