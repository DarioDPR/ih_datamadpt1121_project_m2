<p align="left"><img src="https://cdn-images-1.medium.com/max/184/1*2GDcaeYIx_bQAZLxWM4PsQ@2x.png"></p>

# __ih_datamadpt1121_project_m2__

![diamantes-azules-Juwelo-1](https://user-images.githubusercontent.com/91491555/156051616-62f09381-4664-425c-bb61-6cfc3e971634.jpg)

## **Original Dataset** 
[__diamonds_m2.db__](https://github.com/ih-datapt-mad/ih_datamadpt1121_project_m2/blob/main/db/diamonds_m2.db)

The original Dataset contains seven tables with diamonds attributes such as:

cut= Fair; Good; Very Good; Premium; Ideal

color= J-I-H-F-E-D

clarity= I1-SI1,SI2-VS1,VS2-VVS1,VVS1-IF

depth= (43.0 - 79.0)

carat = weight (0.2 - 4.5)

table =  (43.0 - 95.0)

x = (0.0 - 10.23)

y = (0.0 - 58.9)

z = (0.0 - 8.6)

price (326 - 18823)

city = 'Dubai' 'London' 'Surat' 'Paris' 'New York City' 'Kimberly' 'Zurich'
 'Madrid' 'Antwerp' 'Luxembourg' 'Tel Aviv' 'Las Vegas' 'Amsterdam'

## __Challenge 1: Data Exploration and Preparation__
After joining the tables I used Pandas to analyze the features and their min. max values and to obtain diamonds volume by multypling x,y and z values.

Google search has been useful in order to understand the size carachteristics and scales.

I completed the exploration through Tableau visualizations https://public.tableau.com/app/profile/dario7810/viz/Diamonds_16449568408770/Historia1

It was relevant for me that size attributes have direct impact on price and close realation with aestethical carachteristics: depending on the diamond size some caractheristics are directly affected i.e. color and clarity

## **Challenge 2: BI Report/Dashboard**

https://public.tableau.com/app/profile/dario7810/viz/Diamonds_16449568408770/Dashboard1

I have tried to develop an accessible and easy to use tool to observe the impact of different diamond features on the price.





## **References:**

- [SQLite](https://www.sqlite.org/index.html)

- [SQLAlchemy](https://docs.sqlalchemy.org/en/14/core/engines.html)

- [Visual Analysis Best Practices](https://github.com/ih-datapt-mad/ih_datamadpt1121_project_m2/blob/main/images/visual-analysis-guidebook.pdf)

- [Financial Times Visual Vocabulary](https://github.com/ft-interactive/chart-doctor/tree/master/visual-vocabulary)

- [Matplotlib](https://matplotlib.org/stable/api/index)

- [Pandas Visualization](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.html)

- [Seaborn](https://seaborn.pydata.org/api.html)

- [Plotly](https://plotly.com/graphing-libraries/)

- [Cufflinks](https://coderzcolumn.com/tutorials/data-science/cufflinks-how-to-create-plotly-charts-from-pandas-dataframe-with-one-line-of-code)

- [Tableau](https://github.com/ih-datapt-mad/dataptmad1121_lessons/blob/main/module-2/visualization_tableau.md)

- [Power BI](https://github.com/potacho/power_bi_workshop)
