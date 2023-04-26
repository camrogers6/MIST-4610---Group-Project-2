# MIST-4610---Group-Project-2
Group Members
[@benheick] (https://github.com/benheickMIST-4610-Group-Project)
[@alexiseffenberger] (https://github.com/alexiseffenberger/project)
[@julianneheine] https://github.com/julianneheine/groupProject
[@connorhay] https://github.com/Connor-Hay/SQL-Group-Project

Dataset: World Happiness Index 2013-2023

What are the questions, and why each question is important. Importance can be evaluated and conveyed in a variety of ways including, social, economic, cultural and other factors. Also indicate how they are tied to the data set or sets being used.

The questions we derived from our data set are the following:
1. What is the year where the average world happiness index was the lowest? 
This is important for analyzing what major world events happened during that year to decrease the overall happiness from years prior such as new political leaders coming to power, natural disasters and gun violence.
2. What is the comparison in average happiness between Russia and Ukraine in the past 10 years?
This is important in analyzing if there were any current events that year that would have decreased the happiness index, like the war between Russia and Ukraine and the support the countries received from others.

Describing your dataset and what data it contains: Where was it obtained, what are the dimensions of it (rows and columns), what are the various columns, data types, etc. Describe it in sufficient detail so that an uninformed reader would understand the dataset.

We found our dataset on kaggle.com. There are 4 columns and 1524 rows of data.

Columns: Country – country name
  Data type: text
Year – year of the report
  Data type: year
Index – Happiness Index score
  Data type: float
Rank – country rank according to their Happiness Index score
  Data type: Integer

The happiness index score is calculated based on answers from samples of 1000 people in each country to the main life evaluation question asked in the poll. This is called the Cantril ladder: it asks respondents to think of a ladder, with the best possible life for them being a 10 and the worst possible life being a 0. They are then asked to rate their own current lives on a 0 to 10 scale. Happiness is calculated based on factors such as Dystopia (an imaginary country that has the world’s least happy people; this is used to have a benchmark against which all countries can be favorably compared, and therefore no country performs more poorly than Dystopia) + residuals, which reflect the extent to which the six variables either over or under-explain average 2019-2021 life evaluations, and have a value of approximately 0 over the entire set of countries, GDP per capita, social support, healthy life expectancy, freedom, generosity, and perceptions of corruption. There are other important variables, like unemployment, inequality, and even social media use, that are not included in the dataset because there is not comparable international data in regards to the holistic set of countries.

The manipulations applied to the data set as part of the analysis: Were there any manipulations or calculations that needed to be performed on the data, what were they, describe the purpose and how they were accomplished.

There were no manipulations or calculations performed on this data set. There were 2 downloadable csv files, one containing null values of countries who did not submit a World Happiness Index, and one without null values omitting said countries, which is the dataset we used to calculate our results.

Analysis and Results:

Analyze and visualize the results of your analysis and describe the implications of your analysis. Please provide any citations if required as well as supporting visualizations and analysis generated from Tableau

Question 1 Results

2017 was the year with the lowest average world happiness index which could be due to many major events and factors from that year including multiple deadly hurricanes and earthquakes, many deadly mass shootings, environmental concerns, and major political tensions such as threats from North Korea and the global Women’s March taking place the day after Trump’s inauguration. There were also a series of terror attacks around the UK this year which would not only decrease the UK’s happiness but also of those in other countries constantly having to hear about this news.

Question 2 Results

According to the data, we found it interesting that as tensions have grown between Ukraine and Russia, their happiness ratings are getting closer together, with Russia’s average decreasing and Ukraine’s increasing. This could be because the war created a more unified nation in Ukraine to stand up to Russia. For Russia, their happiness could be decreasing because the people do not want to go to war. Furthermore, in 2014, a war in Ukraine erupted because of Russia’s annexation of Crimea. Armed conflict broke out between the Ukrainian military and Russian-backed forces resulting in a decrease in Ukraine’s happiness rating. Between the years of 2017 and 2018, the United States became involved and imposed sanctions on Russia along with assisting with NATO’s presence in the region. Towards the end of 2018, the US assisted Ukraine by supplying them with lethal weaponry, helping the country overall, and boosting the happiness rating.
