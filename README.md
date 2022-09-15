## Project description:
The goal of this project is to identify patterns that determine whether a game succeeds or not. 
Using user and expert reviews, genres, platforms and historical data on game sales for several years. 
Recomend games that will be sucssesful in the near future.

### Goal:
- Performed statistical comparison between game-genres, rigions and gaming-platforms using Pandas and Numpy.
- Make recommendations backed by statistical inferences for the commercial department.

### Data description:
- Name
- Platform
- Year_of_Release
- Genre
- NA_sales (North American sales in USD million)
- EU_sales (sales in Europe in USD million)
- JP_sales (sales in Japan in USD million)
- Other_sales (sales in other countries in USD million)
- Critic_Score (maximum of 100)
- User_Score (maximum of 10)
- Rating (ESRB) Data for 2016 may be incomplete.

### Steps performed:
- data preparation and cleaning
- EDA
- preform statistical analysis of the data: platforms, rigions and genres
- Create a user profile for each region
- Test the hypotheses

### Results:
**Platform:**
- Need a presence on at least one of the "new-gen" platforms: 'PS4', 'XOne', or 'WiiU'.
- Presence on 'PC' is always good as it is not "aging" like other platforms.

**Region:**
- NA represent ~39% of the gaming market.
- NA and EU together represent ~76% of the market.
- NA and EU have similar preferances.
- JP is hard rigion dominated by its local companies, platforms and genres.

**Genre:**
- Most popular genres are: 'Action', 'Sports' and 'Shooters'.
- Most profitable genres are: 'Shooter' and 'Sports'.
- Genres to avoid (low profitability): 'Adventure', 'Strategy' and 'Puzzle'.
