
# Final Project
## Male vs Female over the years
## Motivation and problem statement: 

Gender Gap is a topic that has been debated for several years. It is potentially very interesting to study the growth or reduction of gender gap over the years. The best way to quantify this is by exploring various areas like health, education, economy and politics. It would also be interesting to see if the world average of these parameters follows the same trends as that of US. 

This will be useful from a human-centered perspective because gender bias has been prevalent in our society since ages. This has given males an advantage over females over the years. But, as women are advancing in various fields, we see the gap diminishing. This project quantifies this decrease/increase in gap and the areas we need to concentrate on to remove this gap

## Data selected for analysis: 

I am planning to use the World Development Indicators(WDI) dataset. I am planning to use this because it has a wide variety of indicators that I can compare to access the stage of males vs females. I can easily apply filters and change the country that I am interested in.

WDI has various indicators related to health, education, economy and politics for various countries of the world from 1960 onwards.

Link [WDI dataset](https://datacatalog.worldbank.org/dataset/world-development-indicators)

License: [CC-BY 4.0](https://datacatalog.worldbank.org/public-licenses#cc-by)


## Unknowns and dependencies: 

The absence of data will impact my ability to complete this project by end of this quarter. I notice that the data is very sparse. If I do not get the data for US and the World for the major parameters like - education, literacy, employement etc. then I may have to change the scope to countries for where data is available. 
Another scenario would be that there is not defined trend in the parameters that indicate the bias. In that case I would have to conclude that there is not general trend of increase/decrease in bias in that particular area of study.

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
     
The 2 analysis questions I will be looking into are:
1. How has the gender gap increased/decreased in these 4 areas?
2. Is the change in these areas same at global level as well as US level?

## Background/Related Work:

My area of research is inspired by the [Global Gender Gap Report](https://en.wikipedia.org/wiki/Global_Gender_Gap_Report#:~:text=The%20report's%20Gender%20Gap%20Index,gender%20equality%20in%20a%20country.&text=Gender%20imbalances%20to%20the%20advantage%20of%20women%20do%20not%20affect%20the%20score.)
This report measures "gender-based gaps in access to resources and opportunities in countries"

The 4 areas mentioned are:

 1. **Economic participation and opportunity:**
 
  The indicators taken into consideration can be found [here](https://tcdata360.worldbank.org/indicators/a07f867b?country=BRA&indicator=28159&viz=line_chart&years=2006,2018#related-link)
  The three concepts taken into consideration: 
      1. Participation gap: Captures difference between women and men in labour force participation rates.
      2. Remuneration gap : Captures difference between women and men in terms of renumeration for same work.
      3. Advancement gap : Captures ratio of women to men among legislators, senior officials and managers, and the ratio of women to men among technical and professional workers.
   
   
 2. **Educational attainment:** 
 
 The indicators taken into consideration can be found [here](https://tcdata360.worldbank.org/indicators/82bb9059?country=BRA&indicator=28160&viz=line_chart&years=2006,2018) It captures the gap between women 's and men 's current access to education through ratios of women to men in primary-, secondary- and tertiary-level education.
 
 3. **Health and survival**
 
     The indicators taken into consideration can be found [here](https://tcdata360.worldbank.org/indicators/e06df634?country=BRA&indicator=28163&viz=line_chart&years=2006,2018)
     Captures life expectancy and sex ratio
 4. **Political empowerment**
 
     The indicators taken into consideration can be found [here](https://tcdata360.worldbank.org/indicators/846d20f8?country=BRA&indicator=27960&viz=line_chart&years=2006,2018). Caputres gap between men and women at the highest level of political decision-making through the ratio of women to men in minister-level positions and the ratio of women to men in parliamentary positions.
     
Taking into consideration the data availibilty and I have shorlisted the indicators:
<table style="border: 1px solid black;">
  <tr style="border: 1px solid black;">
    <th>Indicator</th>
    <th>Description</th>
  </tr>
  <tr>
      <td colspan="2" style="border: 1px solid black;"><b>Economic participation and opportunity</b></td>
  </tr>
  <tr>
      <td>Ratio Of Female To Male Labor Force Participation Rate (%) (Modeled ILO Estimate)</td>
      <td>Labor force participation rate is the proportion of the population ages 15 and older that is economically active: all people who supply labor for the production of goods and services during a specified period. Ratio of female to male labor force participation rate is calculated by dividing female labor force participation rate by male labor force participation rate and multiplying by 100.</td>
  </tr>
  <tr>
      <td colspan="2" style="border: 1px solid black;"><b>Educational attainment</b></td>
  </tr>
  <tr>
      <td>Literacy Rate Female (%)</td>
      <td>Percentage of female population age 7 and above who can read and write. For the purposes of census a person aged seven and above, who can both read and write with understanding in any language, is treated as literate. A person, who can only read but cannot write, is not literate.</td>
  </tr>
  <tr>
      <td>Literacy Rate Male (%)</td>
      <td>Percentage of male population age 7 and above who can read and write. For the purposes of census a person aged seven and above, who can both read and write with understanding in any language, is treated as literate. A person, who can only read but cannot write, is not literate.</td>
  </tr>
  <tr>
      <td>Adjusted Net Enrollment Rate, Primary, Female (% Of Primary School Age Children)</td>
      <td>Adjusted net enrollment is the number of pupils of the school-age group for primary education, enrolled either in primary or secondary education, expressed as a percentage of the total population in that age group.</td>
  </tr>
  <tr>
      <td>Adjusted Net Enrollment Rate, Primary, Male (% Of Primary School Age Children)</td>
      <td>Adjusted net enrollment is the number of pupils of the school-age group for primary education, enrolled either in primary or secondary education, expressed as a percentage of the total population in that age group.</td>
  </tr>
    <tr>
      <td>School Enrollment, Secondary, Female (% Net) </td>
      <td>Net enrollment rate is the ratio of children of official school age who are enrolled in school to the population of the corresponding official school age.</td>
  </tr>
  <tr>
      <td>School Enrollment, Secondary, Male (% Net)</td>
      <td>Net enrollment rate is the ratio of children of official school age who are enrolled in school to the population of the corresponding official school age.</td>
  </tr>
  <tr>
      <td>School Enrollment, Tertiary, Female (% Gross) </td>
      <td>Gross enrollment ratio is the ratio of total enrollment, regardless of age, to the population of the age group that officially corresponds to the level of education shown.</tr>
  <tr>
      <td>School Enrollment, Tertiary, Male (% Gross) </td>
      <td>Gross enrollment ratio is the ratio of total enrollment, regardless of age, to the population of the age group that officially corresponds to the level of education shown.</td>
  </tr>
    <tr>
      <td colspan="2" style="border: 1px solid black;"><b>Health and survival</b></td>
  </tr>
  <tr>
      <td>Sex Ratio At Birth (Male Births Per Female Births)</td>
      <td>Sex Ratio At Birth (Male Births Per Female Births)</td>
  </tr>
    <tr>
      <td>Life Expectancy At Birth, Female (Years)</td>
      <td>Life expectancy at birth indicates the number of years a newborn infant would live if prevailing patterns of mortality at the time of its birth were to stay the same throughout its life.</td>
  </tr>
    <tr>
      <td>Life Expectancy At Birth, Male (Years)</td>
      <td>Life expectancy at birth indicates the number of years a newborn infant would live if prevailing patterns of mortality at the time of its birth were to stay the same throughout its life.</td>
  </tr>
    <tr>
      <td colspan="2" style="border: 1px solid black;"><b>Political empowerment</b></td>
  </tr>
  <tr>
      <td>Proportion Of Seats Held By Women In National Parliaments (%) </td>
      <td>Women in parliaments are the percentage of parliamentary seats in a single or lower chamber held by women.</td>
  </tr>
</table>

It would be interesting to see how these indicators have changed over the years. We could also explore any inter-dependencies.
It would also be interesting to see if the figures follow the same pattern at world and US level.
 
## Methodology :
I will use graphs to study the trend if gender graphs in the 4 areas. Graphs would be the best place to start our analysis. We could dive into the quantitive calculations if we find significant patterns. The indicators where data is present for male as well as female, we could create new indicator which would be a ratio of female to male. Analysing the trends of these ratios will also be useful. I will perform a correlation analysis of all vs all indicatiors. This will help us unearth any inter-dependencies.

Once I have the conclusion for increase/decrease of gender gaps over the years at a world level, we perform the same analysis at the US level. 

This process will answer both our research questions.

## Liscence : 
[MIT](https://github.com/ankitapal189/data-512/blob/main/data-512-a1/LICENSE.md)<BR>
