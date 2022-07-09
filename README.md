**From lunchflation woes to global inflation pains**

**Introduction**

This is my second project as a student with the Lede Program.

My story was inspired by my lunch-flation woes. After paying more for the food that I buy and charging more for the food that I sell, I decided to compare the food inflation rate in Singapore - where I live - to the rest of Southeast Asia, and then the rest of the world.

**Choice of Data Sets**

The main data set used in this project is the latest Food Inflation data from Trading Economics. I find this more useful than the Consumer Price Index (CPI) data that are published by the World Bank and Economist Intelligence Unit (EIU), as the weightage for food items used in the calculation of CPI varies from country to country. I also looked up the Food Price Index data compiled by the Food and Agriculture Organization (FAO), but this data doesn't include a breakdown by country. 

**Data Cleaning and Exploratory Analysis**

Not all entries in the Trading Economics food inflation data have the same reference period. The latest data for most countries were recorded in May or June 2022, but some countries such as Afghanistan, Syria and Myanmar have not published 2022 data yet. I decided to drop countries with no 2022 data from my analysis.

After looking at the mean and median food inflation rates in Southeast Asia, I merged the main data set with a EIU data set that shows how much agriculture accounts for a country's GDP. I didn't see an obvious inverse relationship between a country's agricultural output and its foof inflation rate.

I also looked at the global mean and median food inflation rates, and countries on both ends of the spectrum. I saw a big disparity between countries with hyperinflation and those that are still managing fine. 

Next, I merged this data set with a World Bank classification of countries by their income groups, and looked at the mean and median of high income, middle income and low income countries. 

**Data Visualisation**

The charts, heat map and tables in this story were plotted in Data Wrapper. I did not export these files using ai2html as I wanted to retain the interactive features on the charts / tables, which allow readers to hover over countries on the map and search for a country to find out where it stands in terms of food inflation rate. 

**Contact me**

Got a feedback / question for me?
You can reach me at cpohkwan@gmail.com =)



