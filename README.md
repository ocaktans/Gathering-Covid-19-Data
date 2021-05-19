# Gathering Covid-19 Data

### Gathering case data for Covid-19, changing formats and acquiring new attributes.

### Acknowledgments

###### Most of the data in this repo come from "COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University", link to the repo is https://github.com/CSSEGISandData/COVID-19 

###### Covid-19 data of France come from "Ministère des Solidarités et de la Santé" (Ministry of Health in France).

###### Population data come from United Nations. Dataset of the population is added to this repo (processing of population dataset is not shown here). The link to the page is https://population.un.org/wpp/Download/Standard/Population/

### Contents

###### In this repo, you will find a jupyter notebook that shows the process of data between the sources and the final dataset.

######  Also, a csv file that contains 

       ['Country', 'Date', 'Confirmed', 'Recovered', 'Deaths', 'Active Cases',
       'Death Rate(%)', 'Increase', 'FirstDays', 'day_xth', 'Population_1k',
       'TenCase', 'Cases/1000s']

###### fields which show country names, date of the day, cumulative confirmed cases, cumulative recovered cases, cumulative deaths, active cases, the death rate in percentage, daily increases of the confirmed cases, the day that countries confirmed their first case(s), day count of the countries starting from the 'FirstDays', population in thousands, the day that countries confirmed at least ten cases for the first time, cumulative cases per one thousand people respectively.

### The motivation of the study

###### I've needed to create a Covid-19 dataset for my Design Project at my university. For many reasons, I've faced a lot of problems during the processes. After I've finished it; I've decided to put the data collection part to Python, to create something that I can easily update and show the solutions of the problems that challenged me the most. I've tried to show the causes behind most of the process in the notebook. 
