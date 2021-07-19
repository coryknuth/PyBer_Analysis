# PyBer Rideshare Analysis

We were tasked with analyzing data covering Pyber's ride share business to identify some key areas to focus on to improve the business output. We look at rides broken down by location type, and analyzed aspects such as available drivers in that area, average fares, ride totals, and more. Below we will present a summary of our data, in addition to some reccomendations based on our findings.

## Data Summary

One of the first things that became clear from the data is that Urban areas dominate PyBer's business in both number of available drivers, and number of rides given. As shown in the following two charts. The percentage of total drivers employed by PyBer from Urban areas represent 80% of the total. This then accounts for nearly 70% of all rides given.

<img src="https://github.com/coryknuth/pyber_analysis/blob/41d1cf8e878f6caae4fb947057388fc1cb5a0a69/analysis/Fig7.png" width="600" />

<img src="https://github.com/coryknuth/pyber_analysis/blob/41d1cf8e878f6caae4fb947057388fc1cb5a0a69/analysis/Fig6.png" width="600" />

This makes some sense as Urban areas have the highest population density, and thus demand, for rides. The interesting thing that we discovered is Urban areas only account for 62% of the total fares collected in 2019.

<img src="https://github.com/coryknuth/pyber_analysis/blob/41d1cf8e878f6caae4fb947057388fc1cb5a0a69/analysis/Fig5.png" width="600" />

After some further digging through the data we discovered that while the quantity of rides given in Urban areas is significantly higher, the average fare per ride was higher in suburban areas, and dramatically higher in rural areas. This chart shows the average fare in each city, with the circle size being relative to the available drivers in that city. As it shows, fares on average are much higher into less populated areas.

<img src="https://github.com/coryknuth/pyber_analysis/blob/41d1cf8e878f6caae4fb947057388fc1cb5a0a69/analysis/Fig1.png" width="600" />

We believe this comes down to two primary factors. First, the average distances for rides is likely greater in rural areas given less population and development density. We were not able to confirm this with the dataset we had available, but it is logically supported given other city data. The second primary driver behind this we believe is the scarcity of drivers in a given area. Since rural areas tend to have very few drivers available, the supply and demand curve bends the average fare price up. This is also potentially supported by the wide variance in rural fare rates. At peak demand times, rural areas with their very low driver counts would likely see a price spike. This chart shows there is additional variance in the rural fare averages.

<img src="https://github.com/coryknuth/pyber_analysis/blob/41d1cf8e878f6caae4fb947057388fc1cb5a0a69/analysis/Fig3.png" width="600" />

Ultimately, this difference in average fare, was not signifcant enough to overcome the sheer quantity of rides given in Urban areas from a profit standpoint. Urban areas still provided significantly higher total revenue as shown here.

<img src="https://github.com/coryknuth/pyber_analysis/blob/26abb0fbbd5fcd550bfcad1caf020e5f516e10c1/analysis/fig8.png" width="1200" />

## Recommendations

### 1. Add Drivers to Rural and Suburban Areas
    With the higher average fares in these areas, there is potential for strong increases in total revenue by adding drivers to them. There is a point of diminishing return on       the efficiency of the increase because of lower demand in these areas and eventually creating too much supply, but there appears to be ample room currently for driver growth     in these markets.
    
### 2. Reduce Drivers in Urban Areas
    Oversaturation of drivers in Urban areas may be a concern driving downa average fares, driving down efficency per driver. We think it is worth exploring reducing the             available driver pool during off hours to drive fares up and increase the per ride average fare, without reducing revenue.
    
### 3. Consider Stronger Price Controls to Reduce Variance
    It's possible stronger price control is needed over the fare changes that happen during peak and off hours. We wouldn't want to eliminate this price curve as it is an           important part of the business for both increasing profit and regulating supply against demand using price, however in rural areas there may be too wide of a range of           possible prices. It is worth examining tighting this range to increase profitability.
