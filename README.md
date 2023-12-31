# DATA512_Homework1

# Goal
The objective of this task is to create, evaluate, and share a dataset detailing the monthly page traffic for a chosen collection of English Wikipedia pages, covering the period from July 1, 2015, to September 30, 2023.

# License of the source data 
CC BY 4.0 DEED
Attribution 4.0 International
https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

# Relevant API documentation
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

# Intermediary data files and final output files
<img width="536" alt="image" src="https://github.com/ananya-bajaj-DS/DATA512_Homework1/assets/121599846/56d9100a-3b27-4132-8bf5-dfae6470fe73">

# Data Visualizations
![Plot1](https://github.com/ananya-bajaj-DS/DATA512_Homework1/assets/121599846/ebd27c3e-0afe-4ced-aa4a-d72bb19fcc2e)
![Plot2](https://github.com/ananya-bajaj-DS/DATA512_Homework1/assets/121599846/aae5e150-82c7-49cc-884b-086c44ad09e6)
![Plot3](https://github.com/ananya-bajaj-DS/DATA512_Homework1/assets/121599846/c95e8815-1eaf-4020-8194-7c23fcd0ad91)


# Known issues and special considerations
It's important to note that there might be instances where the view data for certain articles is missing, especially when an article is not accessible for the specific date we are querying. To address this, we've implemented a generic exception handling mechanism that provides information about the reason for the exception and includes the response from the Wikimedia API request.
