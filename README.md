# Relationship between COVID cases and Crime calls count in Seattle, King County, Washington.

# Abstract
In this project I aim to find relationship between the Crime data and COVID19 cases in Seattle. There have been many research been conducted to find the correlation between the COVID cases and Crime calls. We have observed an overall drop in crime but a set of crimes incl. violent crimes, gun, assault have increased.
The Jupyter notebook in the repository contains the details about the project - motivation, datasets, research questions. 
I have worked on an initial EDA and data explaination and then work on the hypothesis. 
I am looking into 3 questions -
1. Was there a significant change in the crime during 2019 and 2020?
2. Is there a relationship between the change in crime vs change in COVID cases?
3. Is there any significant change in a particular type of crime?

# Process 
The data is collected from 2 different sources -
1. ![CDC Data for Weekly COVID cases](https://github.com/avani-bajaj/data-512-final/blob/main/data/PUBLIC_CDC_Event_Date_SARS.xlsx)
2. ![Seattle 911 calls dataset](https://data.seattle.gov/Public-Safety/Call-Data/33kz-ixgy)

You will have to download/export the files in order to work on the dataset. 

After getting the dataset, run the ![jupyter notebook code](https://github.com/avani-bajaj/data-512-final/blob/main/Final%20project.ipynb)

You will be able to follow the markdown/comments along the code and see the plots and insights added in the file. 

# Vizualizations
PFB some plots that show the COVID and Crime trends in Seattle
![COVID Cases](https://github.com/avani-bajaj/data-512-final/blob/main/Plots/Covid_cases.png)

![Daily Crimes](https://github.com/avani-bajaj/data-512-final/blob/main/Plots/Daily_Crime_Count.png)

![Year-on-Year Crime trends](https://github.com/avani-bajaj/data-512-final/blob/main/Plots/Year-on-Year_Trend.png)

![Relationship between COVID and Crime](https://github.com/avani-bajaj/data-512-final/blob/main/Plots/Relationship_COVID_Crime.png)


# Conclusion
We were looking at 3 questions and below are the findings- 
1. Trends before and after COVID - There was a significant drop in cases when COVID started in Feb’20
2. Relationship between the COVID cases being captured in Seattle to the crime cases in Seattle. - We did not observe a significant relationship between the COVID cases being captured to the crime cases.
3. Trends before and after COVID for different crime data call types.
3/10 Priority Type has a significant change in crime post-COVID. As per our expectation, we saw a change in fraud, house crime and narcotics, but there wasn’t a significant drop in crimes like robbery 

# Licence 

We are using CC0 licence for the dataset as it is publically available.  https://github.com/avani-bajaj/data-512-final/blob/main/LICENSE






