# Final-Project

### [Results of the Project](https://public.tableau.com/views/Final-Project_16780679054800/Story?:language=en-US&:display_count=n&:origin=viz_share_link)

## Status

#### The current status of the project is minimum viable product stage, but it is working perfectly.

#### Although the project is still in its early stages, it is working perfectly and meets all the initial requirements. I am continuing to refine and improve the analysis as I gather more data and feedback. I am confident that the final product will provide valuable insights and meet the project objectives.

## Selected topic

#### The main topic of the project is to create a tool that evaluates the macroeconomic conditions of different countries and industries, by analyzing news articles through PESTEL analysis, to identify potential opportunities for entrepreneurship.

## Reason why of the selected topic

#### The main topic of the project is to create a tool that analyzes the macroeconomic environment of different countries and industries and provides a guide for individuals or businesses to identify countries with the best economies and growth potential, as well as the most beneficial industries in each case. The tool uses data from the World Bank database and news articles obtained through the Bing API to evaluate the political, economic, social, technological, environmental, and legal aspects of the chosen countries and industries, and to predict their overall health score. The project involves data cleaning and preprocessing, data analysis, machine learning, and data visualization. 

#### The selected topic is valuable because it addresses a common challenge for entrepreneurs who want to expand their businesses into new countries or industries, but are unsure where to start due to the lack of knowledge and insights into the economic and social conditions of those areas. By leveraging PESTEL analysis and the Bing Search API, the project aims to provide a comprehensive and up-to-date evaluation of various countries and industries, allowing entrepreneurs to make more informed decisions about where to invest their time and resources.

## Overview:

#### This project aims to analyze news articles and economic data to gain insights for making investment decisions. By leveraging machine learning techniques and domain knowledge, we aim to identify trends and patterns that can inform investment strategies in various sectors and countries.

## Data Sources:

### The project will use data from multiple sources, including:

#### World Bank API: to obtain economic indicators such as GDP growth, ease of doing business, and industry size for different countries and sectors.

#### https://documents.worldbank.org/en/publication/documents-reports/api

#### Bing News Search API: to retrieve news articles related to specific countries and sectors.

#### https://www.microsoft.com/en-us/bing/apis/bing-news-search-api

#### CSV Trained Data: Twitter trained data to use for the machine learning

#### http://help.sentiment140.com/for-students/

#### Excel file: containing a sample dataset of news articles, their sentiment score, and their corresponding country and sector.

## Description of the sources of data

#### The project uses several sources of data. The World Bank database is used to extract information related to the GDP and GDP growth rate of various countries. The Ease of Doing Business score is also obtained from the World Bank database. Bing Search API is used to extract news articles related to specific industries and countries. Finally, a labeled dataset of news headlines categorized as positive or negative is used to train a machine learning model for sentiment analysis, this database comes from tweets from http://help.sentiment140.com/for-students/

## Questions to Answer:

### The project aims to answer several questions to help entrepreneurs make informed decisions. Some of these questions include:

#### What are the top countries to invest in based on their GDP, GDP growth rate, and ease of doing business score?
#### What industries are thriving in these countries?
#### What is the current state of the political, economic, social, technological, environmental, and legal (PESTEL) factors for each country and industry?
#### What are the most relevant and recent news articles related to a particular country, industry, and category?
#### What is the sentiment of the news articles related to a particular country, industry, and category?

## Approach:

### To answer these questions, we plan to follow the following approach:

#### Data collection: Obtain relevant data from the World Bank API, Bing News Search API, and the provided Excel file.
#### Data preprocessing: Clean and preprocess the data to ensure consistency and compatibility across different sources.
#### Data analysis: Use machine learning techniques to classify news sentiment and identify trends and patterns in the economic data.
#### Visualization: Present the results in a clear and concise way, using charts and graphs to highlight key insights.
#### Reporting: Write a report summarizing the findings and conclusions, and providing recommendations for investment strategies.

## Steps to complete this analysis

#### 1. Extract the GDP (current US$) for 2021 for each country from the World Bank database and keep the top 25 countries.
#### 2. Evaluate the GDP growth (annual %) of the last 6 years from 2021 for all the countries and keep the top 25.
#### 3. Merge both tables and keep the countries that are in both.
#### 4. Obtain Ease of doing business score (0 = lowest performance to 100 = best performance) from the World Bank database and keep only the countries with a score greater than 77.
#### 5. Merge the databases again to only keep the top 3 countries evaluating these three characteristics.
#### 6. Choose all the industries that currently exist according to the World Bank.
#### 7. Create a database that makes all the combinations between the chosen countries, the existing industries and the categories to study PESTEL (political, economic, social, technological, environmental and legal).
#### 8. Use the Bing API to get the most relevant and current news related to the country, industry and category to study.
#### 9. Use a dataframse with headlines categorized between positive and negative to train a machine learning model to be able to categorize the headlines of the extracted news.
#### 10. Export the trained data and the dataframe with the news to the database for the project on pdAdmin using Python and then Import them back to use them on the Machine Learning Model.
#### 11. Categorize the news and calculate an overall health score for each aspect of PESTEL for each industry and each country.
#### 12. Send the output of the data processing in python to the database to be compiled in Tableu.
#### 13. Use Tableau to display the results in graphs and a matrix that shows the industries by country with the score obtained in each aspect of the PESTEL and a general score.

## Communication Protocols:

#### The communication between the various components of the project likely involves API calls, such as the Bing Search V7 API, to retrieve and process data from various sources. The data is then processed using Python programming language, and the results are visualized using Tableau.

#### As the sole member of this project, I will communicate with myself through a project management tool (e.g., Trello) to keep track of tasks, deadlines, and progress. I will also maintain a daily log to record my thoughts, observations, and insights as I work on the project.

#### As the only person working on this project, I have established communication protocols with myself to ensure that I can complete the project on time. I have set goals and deadlines for each phase of the project and I have been tracking my progress regularly. Whenever I face any challenges or have questions, I document them and find solutions by conducting research and consulting relevant resources. Additionally, I prioritize my tasks based on their urgency and importance and I make sure to take breaks and maintain a healthy work-life balance to avoid burnout. Through these protocols, I am confident that I can successfully complete the project within the given timeframe.

## Conclusion:

#### By analyzing news articles and economic data, we aim to provide insights and recommendations that can inform investment decisions and help achieve better returns. The project will leverage machine learning techniques and domain knowledge to identify trends and patterns that might not be visible through traditional methods of analysis.

## Results:

##### Before starting the visualization of the processed data, these were stored in a database, in a one-to-one and one-to-many relationship. Subsequently they were sent to Tableu and here you can see their visualization before starting to visualize them.

![4](https://github.com/jjgomezg17/Final-Project/blob/main/Images/4.png)

![5](https://github.com/jjgomezg17/Final-Project/blob/main/Images/5.png)

![6](https://github.com/jjgomezg17/Final-Project/blob/main/Images/6.png)

#### Selection of countries that belong to the top 25 of GDP and its growth and that are countries where it is easy to do business

##### This is a selection process of countries that fulfill certain criteria. Specifically, the selected countries must be among the top 25 in terms of GDP and GDP growth. Additionally, they must be countries where it is easy to do business. This selection process aims to identify countries that have a strong economic performance and are also conducive to business development.

![1](https://github.com/jjgomezg17/Final-Project/blob/main/Images/1.png)

#### PESTEL Analysis by Country and Sector

##### This is a project that involves conducting a PESTEL analysis for different countries and sectors. PESTEL stands for Political, Economic, Social, Technological, Environmental, and Legal factors that can affect the business environment of a country or a sector. The analysis will be conducted on various countries and sectors, and the sentiment of the news articles will be added to the analysis to see the score by each country and sector on each section of the analysis. The aim is to provide insights into the business environment of each country and sector and identify areas of opportunity or potential risk.

![2](https://github.com/jjgomezg17/Final-Project/blob/main/Images/2.png)

#### Overall Score based on PESTEL Analysis, by Industry and Country

##### This analysis aims to provide an overall score based on the PESTEL analysis for each country and industry. PESTEL analysis is a framework that helps identify the political, economic, social, technological, environmental, and legal factors that affect an industry or country.

##### By analyzing the sentiment of the news articles related to each country and industry, we can evaluate the overall impact of these factors on the industry in that country. The sentiment is then averaged for each section of the PESTEL analysis (political, economic, social, technological, environmental, and legal) to create an overall score.


##### This overall score helps to identify which countries and industries are more favorable for business and investment opportunities, based on the PESTEL factors that affect them.

![3](https://github.com/jjgomezg17/Final-Project/blob/main/Images/3.png)
