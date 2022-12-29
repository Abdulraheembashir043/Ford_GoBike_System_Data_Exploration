# Ford GoBike System Data Exploration
> **BY ABDULRAHEEM BASHIR**


## Dataset

- This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

## Data Wrangling

- I attempted to comprehend my dataset by examining its structure, identifying the core feature(s) of interest, and aspects that can aid in the study.
- The data contains some datatype misrepresentation, some missing values, some columns that are unnecessary, and some columns that must be formed from the given column, all of which are dealt with appropriately in the data cleaning section.


## Summary of Findings

### Univariate Exploration
Following are the findings from this section:
- The top 10 most popular start stations are shown in the first chart above, with 'Market ST at 10th St' having the most start trips and 'Stewart St at Market St' having the fewest.
- The top 10 most popular end stations are shown in the second chart above, with 'San Francisco Caltrain Station 2 (Townsend St at 4th St' having the most end trips and 'Powell St BART Station (Market St at 5th St)' having the fewest.
- It's also worth noting that 'Market St at 10th St', 'San Francisco Caltrain Station 2 (Townsend St at 4th St)', 'Montgomery St BART Station (Market St at 2nd St)', and 'Powell St BART Station (Market St at 4th St)' all rank in the top 5 for both start and finish stations.
- Most journeys take less than 1000 seconds, and only a small number take longer than 2000 seconds.
- Majority of members are 20-40 years old, male, belong to the subscriber category, and did not share the bike for the entire journey.

### Bivariate Exploration
Following are the findings from this section:
- Youthful members are more willing to share the bike.
- There is a weak negative association between duration and age. The trip lasts less time as the member becomes older.
- Only subscribers shared bikes, and no customers ever shared a bike for the entirety of the trip.
- The majority of bike-sharing riders are in their twenties.
- Bike sharing is limited to subscribers, which makes sense.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.