## Home, Home Alone: A Machine Learning Approach to Tackle Inefficiencies in the Real Estate Market
=========================

### Project Overview:

#### Problem Area:
There are many challenges within the real estate market. We can take a look at the challenges faced by both sides: sellers who are listing new properties and buyers who are looking to acquire new properties. Some of the main problems faced by buyers include: housing affordability, Limited Inventory, Emotional Stress and Decision Fatigue, and Location Constraints. Some of the main problems faced by sellers Unused Inventory, Poor Marketing, and Volatile Markets. Furthermore, the Covid pandemic largely affected both sides of the housing market, creating instability in the median prices of properties. 

#### Users affected:
The users in the United States directly affected by this problem are individuals/families that are looking to purchase a property as well as the sellers (in our case interested in the real estate agents) that have listed a new property for sale. 

#### Proposed Data Science solution:
Given a sufficiently large dataset, one can deeply analyze the housing market in the United States over the most recent decade, determine key patterns in terms of inventory, prices across property types, and demand (number of properties sold) across different regions, and use machine learning to make predictions about these variables in the future.

#### The impact of my solution:
Improving the accuracy of a machine learning model with the goal of significantly surpassing baseline accuracy across predicting inventory, property sale prices, and number of property sales would greatly serve millions of buyers and sellers in the United States, potentially generating hundreds of millions of dollars by making better use of inventory resources, marketing strategies, and decreased number of pending sales. 


#### Description of dataset:
The raw data set was attained from Kaggle.com and it was gathered by Redfin, a real estate brokerage company with an online platform connecting users to listed properties as well as real estate agents. The data set is freqently updated with ranges between 2012 and early 2024. Additionally, it contains over 5 million rows and 58 columns. 

Here is a description of the columns of interest:
1. city (object): A particular city in the United States
2. state (object): A particular state in the United States
3. property_type (number): Category of property (e.g. multifamily)
4. median_sale_price (number): The median sale price for the property type 
5. median_list_price (number): The median listing price of a property type
6. median_ppsf (number) The median sale price per square footage of a property
7. median_list_ppsf (number) The median listed price per square footage of a property type
8. homes_sold (number): The total number of homes sold for a property type within the month since the date listed
9. pending_sales (number): The total number of pending sales for a property type within the month since the datae listed
10. new_listings (number): The total number of new listings for a property type within the month since the datae listed
11. inventory (number): The raw count of the number of properties being actively marketed and listed for sale
12. months_of_supply (number): The number of months it would take for the current inventory of homes on the market to sell given the current sales pace
13. median_dom (number): The median days on market. A statistic used to measure how many days a property takes to sell or be taken off the market
14. avg_sale_to_list (number): The sale-to-list ratio is the final sale price (what a buyer pays for the home) divided by the last list price
15. sold_above_list (number): The sold-above-list ratio is the proportion of of properties sold above their listed price
16. price_drops (number): The proportion of of properties whose asking price was lowered 
17. off_market_in_two_weeks (number): The proportion of homes that go under contract within two weeks of being listed, meaning the seller has accepted an offer from a buyer
18. parent_metro_region (number): Surrounding region
19. date (datetime): When the information was gathered


### Demo

... Show your work:
...     Data visualizations
...     Interactive demo (e.g., `streamlit` app)
...     Short video of users trying out the solution


### Methodology

... High-level diagrams of entire process:
...     various data processing steps
...     various modelling directions
...     various prototyping directions


### Organization

#### Repository 

* `data` 
    - contains link to copy of the dataset (stored in a publicly accessible cloud storage)
    - saved copy of aggregated / processed data as long as those are not too large (> 10 MB)

* `model`
    - `joblib` dump of final model(s)

* `notebooks`
    - contains all final notebooks involved in the project

* `docs`
    - contains final report, presentations which summarize the project

* `references`
    - contains papers / tutorials used in the project

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `conda.yml`
    - Conda environment specification

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

#### Dataset

... Google Drive links to datasets and pickled models

### Credits & References

... Include any personal learning
