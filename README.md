# Project Proposal --AD5

## Project Description

### Target audience
With the growing popularity of **cryptocurrency**, more and more people want to know what it is and how to start investing in it. The main audiences of our project are those **intersted in investing in cryptocurrency**, or **cryptocurrency owners** who _constantly need to check the exchange rates_ and _compare the real time status of different markets_.

### What can the audience learn?
Our audience will learn a lot about the current and past states of specific cryptocurrencies through our data. Three specific questions that our project can answer for our audience are: 
- How do specific coins compare to each other (present and past) in terms of exchange rates?
- What do the current order books look like for any given coin? 
- What is currently being tweeted about cryptocurrency?


&nbsp;


## Technical Description

### Data Wrangling
After retrieving data from the API, we would need to **reshape** our data so that it could be easily readable for our users. For example, after we get the exchange rates of different cryptocurrencies, we will _separate them into different dataframes_ and _calculate summary information_ about each type of cryptocurrency. We will also **visualize** the data so that our users can easily see the trends of different cryptocurrencies. For exchange rate of one specific cryptocurrency, we will _compare its current rate to its historic rate_ and _generate a line plot_.

### Major Libraries
 
We believe that the best way to display such a plethora of data would be through visual charts and/or graphics. This is why we have chosen to use **ggplot2** and **plotly** to create data visualizations to help our audience understand what is currently going on within the world of cryptocurrency. These visualizations will also help reveal different trends or patterns by using both current and historical data. 