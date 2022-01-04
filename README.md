# Forecasting_Covid19_VaccincationRate
**Objective:**
- Forecast vaccination rates using data science or machine learning algorithms in order to determine the impact of vaccination on our daily lives.
- Mainly compare the situation under Canada and India.
- Examine correlations between vaccination and new death rate to get insights on how healthcare system, government, and industry can tackle this growing problem through increased immunization.

**Attachments:**
- **Covid19-vaccination.csv:** Official daily data for 218 countries collated by the Our World in Data team. Obtained from the link: https://github.com/owid/covid-19-data/tree/master/public/data/vaccinations
- **Complete_covid19_dataset.csv:** The complete official dataset.

**Process:**
- Clean up the missing dataset. Customize the data cleaning pipeline, examine the correlation matrix between the features, perform statistical tests to determine the similarity between their distributions, and then decide how to fill.
- Visualize how different regions/continents implement and polularize the vaccinations. Visualize how's the effectiveness over time regarding to daily vaccination among different countries.
- Select time-series ARIMA model by parameters estimation, diagnostic checking, and forecasting vaccination scenarios (best, base, worst) for Canada and India.
- Relate the vaccination rate to new death rate to check the effect of vaccination under two countries.

**Findings:**
- Asia has the highest number of people vaccinated which could be due to its most-populous characteristic. Then the second top region Europe performs quite well as it doesn't have high total population originally but has second highest number of people vaccinated.

- Due to distinct paces and policy phases on speed of implementing vaccinations, China performs the best as there's an almost exponential increase of the vaccination rate. Then India also has an evident increase of rate in recent days. However, notice that Japan, Bangladesh, and Vietnam end much eariler compared to any other country more likely due to the lack in supply of vaccinations.

![alter text](https://github.com/elenayinyin/Forecasting_Covid19_VaccincationRate/blob/main/daily_vacc.png)

- Choose the best model ARIMA(5, 2, 4) based on AIC score. Forecast the daily vaccination rate for the following 50 days in Canada and India.

- Although India has huge population as a developing country, it would perform surprisingly well in the increasing speed of daily vaccination, even faster than Canada.

-  To further see the effect of vaccination on new death rate, we fit the exponential curve to the data. Observe that India has a more effective vaccination program because it responds quickly to suppress the death rate, controls the death rate as low as possible in long term, and ensures the death rate do not bounce back or do bounce in the smallest scale.



