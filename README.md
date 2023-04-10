# Social-analysis-of-penis-length-worldwide


- [@paulaalvarezsa](https://github.com/paulaalvarezsa)



This is a project that through a process of **ETL** by **scraping**, **API** and CSV data sources, along with visualization with Matplotlib and Tableau, relates different sociological variables with the **average penis length** per country.

The different cross data are: 

1. Relationship between country average penis length and per capita income.

2. Relationship between country average penis length and life expectancy.

3. Relationship between life expectancy and per capita income.

4. Difference between penis measurements between data extracted by self-measurement and individual self-reporting of the measurement and data extracted by institutional measurements.

## Hypothesis



## Analysis process

| Table | Type     | Description                |Metod|
| :-------- | :------- | :------------------------- |:-------  |
| penis | CSV | Average penis length per country in the 2000s | Kaggle |
| life_exp | CSV | Life expectancy. per country in 2022 | Scraping |
|  gdp| CSV| Per capita income per country in 2022 |API |


## Discoveries

![relationship_between_variables.png](https://github.com/paulaalvarezsa/Social-analysis-of-penis-length-worldwide/blob/main/images/relationship_between_variables.png)

![map_length_mixflaciderect_by method.png](https://github.com/paulaalvarezsa/Social-analysis-of-penis-length-worldwide/blob/main/images/map_length_mixflaciderect_by%20method.png)


## Conclusions

Based on my analysis using Python, pandas and web scraping techniques, I have found that there is no significant difference in length measurements reported by individuals themselves versus those measured by external organizations. Our data indicates that both self-reported and externally measured lengths are generally similar, suggesting that the accuracy of length measurements is not significantly affected by the measurement method.

I also cross-referenced the results with data on life expectancy by country. My analysis found no significant correlation between length and life expectancy, indicating that length is not a significant predictor of health or longevity.

While length has been previously suggested as a potential indicator of health outcomes and socioeconomic status, my findings suggest that this relationship may not be as strong as previously thought. Further research is needed to better understand the factors that contribute to health and longevity, including genetic, environmental, and lifestyle factors.

Our study provides important insights into the relationship between length and health outcomes, and highlights the value of using data analysis tools like Python and web scraping to explore complex relationships in large datasets.

In addition to analyzing length and life expectancy data, we also examined the relationship between  length and per capita income, and the relationship between per capita income and life expectancy. Our analysis found no significant correlation between length and per capita income, indicating that  length is not a reliable indicator of socioeconomic status.

However, we did find a significant positive correlation between per capita income and life expectancy, suggesting that higher income levels are associated with greater health outcomes and longevity. This finding supports previous research on the relationship between income and health, and underscores the importance of addressing socioeconomic disparities in public health initiatives.

Our study provides a comprehensive analysis of the relationships between length, per capita income, and life expectancy, and highlights the potential of data analysis tools like Python and web scraping for understanding complex relationships in large datasets.