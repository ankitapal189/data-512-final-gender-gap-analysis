
# Project
## Gender Gap Analysis using WDI Data
Ankita Pal

## Abstract: 

Gender Gap is a topic that has been debated for several years. It is potentially very interesting to study the growth or reduction of gender gap over the years. The best way to quantify this is by exploring various areas like health, education, economy and politics. It would also be interesting to see if the world average of these parameters follows the same trends as that of US. This will be useful from a human-centered perspective because gender bias has been prevalent in our society since ages. This has given males an advantage over females over the years. But, as women are advancing in various fields, we see the gap diminishing. This project quantifies this decrease/increase in gap and the areas we need to concentrate on to remove this gap. I have identified 6 indicators related to the 4 major areas mentioned in the report for my analysis.

I found that All the 4 areas - Economic participation and opportunity, Educational attainment, Health and survival, Political empowerment have shown a reduction in gender gap at World level. At US level Economic participation and opportunity shows an increase in gender gap whereas other areas show a decrease in Gender Gap. At the world level, all the indicators have a linear correlation with each other with the exception of Participation Gap which shows parabola-like relationship with all others.

These results help us identify the areas we need to work on to reduce gender gap at the World as well as US level. Also it discovers relationships between indicatiors
## Data selected for analysis: 

I am planning to use the World Development Indicators(WDI) dataset. I am planning to use this because it has a wide variety of indicators that I can compare to access the stage of males vs females. I can easily apply filters and change the country that I am interested in.

WDI has various indicators related to health, education, economy and politics for various countries of the world from 1960 onwards.

Link [WDI dataset](https://datacatalog.worldbank.org/dataset/world-development-indicators)

License: [CC-BY 4.0](https://datacatalog.worldbank.org/public-licenses#cc-by)


## Research questions and/or hypotheses:

I have identified the indicators related to the 4 major areas mentioned in the report.
 1. Economic participation and opportunity:
     1. Labour force participation
 2. Educational attainment
     1. Literacy rate
     2. Enrolment in primary education
     3. Enrolment in secondary education
     4. Enrolment in tertiary education
 3. Health and survival
     1. Sex ratio at birth
     2. Life expectancy
 4. Political empowerment
     1. Proportion of seats held by women in national parliaments (%)
     
The 3 analysis questions I looked into are:
1. How has the gender gap increased/decreased in these 4 areas?
2. Is the change in these areas same at global level as well as US level?
3. Are there correlations between any pairs of indicators at the world level?

 
## Methodology :

I will use graphs to study the trend if gender graphs in the 4 areas. Graphs would be the best place to start our analysis. We could dive into the quantitive calculations if we find significant patterns. The indicators where data is present for male as well as female, we could create new indicator which would be a ratio of female to male. Analysing the trends of these ratios will also be useful. I will perform a correlation analysis of all vs all indicatiors. This will help us unearth any inter-dependencies.

Once I have the conclusion for increase/decrease of gender gaps over the years at a world level, we perform the same analysis at the US level. 

This process will answer both our research questions.

## Data  

I used the World Development Indicators(WDI) dataset. I used this dataset because it has a wide variety of indicators that I can be compared, to access the stage of males vs females. I easily applied filters and changed the country that I am interested in.

WDI has various indicators related to health, education, economy and politics for various countries of the world from 1960 onwards.

Link [WDI dataset](https://datacatalog.worldbank.org/dataset/world-development-indicators)

## Directory structure
.
    ├── ...
    ├── data                    
    │   ├── WDIdata.csv              
    │   └── ...                 # etc.
    └── ...

## Liscence : 

Data: [CC-BY 4.0](https://datacatalog.worldbank.org/public-licenses#cc-by)

MIT: [MIT](https://github.com/ankitapal189/data-512/blob/main/data-512-a1/LICENSE.md)<BR>
