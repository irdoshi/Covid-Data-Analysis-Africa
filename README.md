# Covid-Data

In this project, the objective was to analyze and manipulate a COVID-19 dataset for African countries. The dataset contained information regarding confirmed cases and deaths in various countries. The following steps were taken:

- Loaded the list of African countries from the "countries-africa.csv" file.
- Determined the total number of African countries listed in the file.
- Collected the names of COVID data files (starting with "covid-global") into a character vector.
- Extracted African countries from the COVID data by loading the COVID data file for October 2021.
- Identified the African countries present in the COVID data for October 2021.
- Determined the number of African countries found in the COVID data.
- Identified the African countries that did not match with the COVID data.
- Amended the list of African countries by identifying how these countries were written in the COVID data.
- Adjusted the list of African countries to match the names used in the COVID data.
- Verified the effectiveness of the amended list by identifying the remaining unmatched countries.
- Loaded and merged all datasets.
- Extracted the date part from the first file name and converted it to a Date object.
- Created an empty dataset for the final merged data.
- Looped over all the COVID data files, loaded each file, extracted data for African countries, and selected the number of deaths.
- Extracted the year and month from the file name and added them to the extracted data.
- Merged the extracted data with the final dataset.
- Displayed the time series by extracting the population size for each African country.
- Computed the death rate for each country by dividing the number of deaths by the population.
- Determined the top 10 countries with the highest death rates.
- Created a plot showing the growth of death rates over time for these 10 countries.
- Computed the number of new monthly deaths per 1 million population and displayed it on the plot.
- Identified the country among the top 10 with the highest peak in new monthly deaths and determined the timing of that peak.
