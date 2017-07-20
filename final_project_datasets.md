# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Final Project Datasets

# Overview

We have sourced four final project datasets, as well as three additional "stretch" datasets. All datasets are available through Sailfish at this [link](https://public.sailfish.boozallen.com/exchange/nets/177085/catches).

## Option 1: Amazon Pricing Data

From ProPublica:

> ProPublica reporters examined Amazon’s shopping algorithm. We scraped data from the company's website to examine listings for 250 bestselling products across a wide range of categories, from electronics to household supplies, over a period of several weeks during summer 2016. We compared pricing and shipping costs for products offered by multiple vendors, including those sold by Amazon, sellers in the "Fulfilled by Amazon" program. In total, we examined 6,973 vendor listings.

Possible areas to examine:

- How does vendor affect price?
- How does rank affect an item's price? Or vice versa?

## Option 2: Health Insurance Marketplace

From Kaggle:

> The Health Insurance Marketplace Public Use Files contain data on health and dental plans offered to individuals and small businesses through the US Health Insurance Marketplace.

Possible areas to examine:

- How do plan rates and benefits vary across states?
- How do plan benefits relate to plan rates?
- How do plan rates vary by age?
- How do plans vary across insurance network providers?

Note: this dataset is quite large, and taking a random 10% sample by state (with justification) is optional.

## Option 3: 3 Million Instacart Orders

Instacart open sourced 3 million of their orders from their databases. It is recommended that you read more via their engineering blog [here](https://tech.instacart.com/3-million-instacart-orders-open-sourced-d40d29ead6f2).

Possible areas to examine:

- How does time of day affect an order?
- What types of items are most often reordered?
- How many different cart sizes there appear to be among buyers, and what meaningful differences exist in those basket of goods?
- How does order affect when a user adds something to cart?

Note: this dataset is quite large, and taking a random 10% sample by state (with justification) is optional.

## Option 4: 

From Kaggle:

> These files contain complete loan data for all loans issued through the 2007-2015, including the current loan status (Current, Late, Fully Paid, etc.) and latest payment information. The file containing loan data through the "present" contains complete loan data for all loans issued through the previous completed calendar quarter. Additional features include credit scores, number of finance inquiries, address including zip codes, and state, and collections among others. The file is a matrix of about 890 thousand observations and 75 variables. A data dictionary is provided in a separate file.

Possible areas to examine:

- What factors most explain on-time loan repayments?
- As a bank, what evaluation metric would you opt for to determine if a given load should be given? As a consumer, what evaluation metric would you opt for to determine if a given loan should be given? How does this affect your model's performance?


# Additional Options

These datasets are listed in the estimated order of feasibility of analysis for your final project. The reason they are considered auxiliary is noted on a dataset-by-dataset basis. Even if you are unable to action the needs for each of these given datasets, know that additional practice of this class's techniques will unlock the skills necessary to complete a final project on any of the below.

## Option 5: Fuel Economy Data

The US Environmental Protection Agency publishes miles per gallon data following tests of vehicles on the road in the U.S. Datasets from the years 2000 - 2018 for all make and models are readily accessible.

Possible areas to examine:

- Predict the miles per gallon of a given brand and car type
- Create a cross-sectional look at how car efficiencies have improved over the years. Predict future miles per gallon for models, brands, or car types.
- Predict the carbon impact for a given brand or car type.

**Why this is in the 'Additional Section':** The multi-year nature of the dataset may prove to be a data wrangling challenge. (Nonetheless, the overall size of the data among years makes it approachable, perhaps more so than prior options.) Moreover, forecasting is not explicitly covered in this portion, so model selection may be a panel OLS by year or a decision tree regressor.

## Option 6: Craft Beers

Craftcans.com maintains a continuously updated dataset of, currently (as of July 2017), 2962 craft beers. The data contains the beer name, brewery, location, style, size, ABV, and IBUs.

Possible areas to examine:

- Predict the ABV based on other factors
- Cross reference this data with the [ratebeers.com API](https://www.ratebeer.com/api.asp) to predict quality of beer by other factors provided

**Why this is in the 'Additional Section':** The multi-year nature of the dataset may prove to be a data wrangling challenge. (Nonetheless, the overall size of the data among years makes it approachable, perhaps more so than prior options.) Moreover, forecasting is not explicitly covered in this portion, so model selection may be a panel OLS by year or a decision tree regressor.

## Option 7: All Trump Tweets

A live updating JSON database of all of President Donald J. Trump's tweets is available. The data also includes basic metadata: time tweeted, retweets, favorites, and more. The dataset is updated hourly.

Possible areas to examine:

- How does specific wordchoice affect engagement?
- How does wordchoice change over time?

**Why this is in the 'Additional Section':** Natural language processing is taught relatively late in the lessons. Thus, this dataset relies on an aggressive back-loaded project schedule. Moreover, this data is all available in JSON, meaning the user will need to independently explore using Pandas or the `JSON` package in Python to read in the data. This is a great example of a dataset you should use to continue practicing your learnings.
