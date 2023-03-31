
# King County Residential Real Estate Anlaysis

![img](/Images/seattle_readme_image.jpeg)

**Author**:

Clara Giurgi
<br>
Stephanie Ciaccia

## Overview

Panda Real Estate is a residential real estate firm that prioritizes leveraging technology to enhance and optimize their real estate portfolio. Historically operating in the greater New York City Area, Panda Real Estate has decided to expand it's portfolio to the west cost, to include properties in King County, Washington.

## Business Problem

As Panda Real Estate expands it's market to the greater Seattle Metropolitan area, we will be identifying the key variables that influence residential home prices in King County, Washington. By conducting a thorough exploration of the various variables that can impact home prices, we hope to inform internal investment teams on the residential housing market.

## Data

- **King County Data** We used a dataset from [King County Open Data](https://gis-kingcounty.opendata.arcgis.com/) that includes over 30K home sales from 2021-2022. Variables inlcuded in this dataset include a variety of physical and environmental variables such as: $27,000 - $30,000

- **FRED Economic Data** This dataset was pulled from [Economic Research - Federal Reserve Bank of St. Louis](https://fred.stlouisfed.org/series/MORTGAGE30US). In includes monthly mortage rates from the past 30 years.

## Methods

To perform our inferential analysis, we created a simple linear regression and a multiple linear regression. This model was used to examine the relationship between the price, our dependent variable, and a variety of independent variables. The main variables we used in the model were:


## Results

- **Home Size** - Increasing footage of home by approximately 964sq.ft increases the price by a factor of 1.227 or <b>22.7%<b>.

![img](/Images/median_sqft_vs_price.png)

- **Proximity to Seattle** - When compared to our reference point of zip code 98001, Auburn, which is associated with the city of Federal Way, we observed that relocating to zip codes located to the north and closer to Seattle, as well as more urban cities like Kirkland (98033), results in a <b>22.7%<b> increase in the sale price. Conversely, if one were to remain in close proximity to Federal Way and avoid Seattle, there would be a slight decrease in sale prices. This is evident from the comparison to zip code 98002, which corresponds to Auburn city and resulted in a price decrease of <b>1.04%<b>.

![img](/Images/median_zip_code.png)

- **Construction grade quality.** - It is evident that the quality of construction has a significant impact on prices. A decline in construction quality is linked to a reduction in sale prices. The transition from a construction grade of 10 to 7 results in a decrease of <b>13.3%<b> in prices.

![img](/Images/median_price_grade.png)


## Conclusions

As a result of this analysis, three variables have been identified that can impact prices and should be taken into consideration when researching potential investment properties:

- **Home Size** There is a direct correlation between the sq. ft. of the home and the sale price. Larger homes have higher sale prices. Increasing footage of home by approximately 964sq.ft increases the price by a factor of 1.227 or <br>22.7%<br>.
    
- **Proximity to Seattle** Homes closer to Seattle have higher sale prices. Comparing to our baseline zip code 98001 which corresponds to Federal Way city, moving to zip codes that are north and with more proximity to Seattle and more uban cities such as Kirkland (98033) increases the sale price by 22.7%. Alternatively, staying close to Federal Way and away from Seattle, sale prices slightly decrease. As we can see by the comparison to zip code 98002 which corresponds to Auburn city which decreased price by 1.04% .<br>

![img](/Images/king_county_map.png)

- **Construction grade quality **It is evident that the quality of construction has a significant impact on prices. A decline in construction quality is linked to a reduction in sale prices. For instance, the transition from a construction grade of 10 to 7 results in a decrease of <br>13.3%<br> in prices.

### Next Steps

To gain a more comprehensive understanding of changing home prices, it would be beneficial to analyze additional historical home sale data beyond the current dataset that only spans 12 months. Reviewing home sales over the past 5-10 years can provide insights into how the housing market has evolved.

In addition to historical data, conducting further analyses of environmental variables can enhance our understanding of residential home prices and should be taken into consideration. Some factors to consider include:

- School district ratings and locations
- Tax data
- Population data

## For More Information

See the full analysis in the [Jupyter Notebook](https://github.com/claragiurgiu/Phase2-Project/tree/main)

## Repository Structure

```
├── data
├── images
├── __init__.py
├── README.md
├── Presentation.pdf
└── Final_Kings_County_Analysis.ipynb