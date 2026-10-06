Data Source:

I originally found a link to a GitHub repository from the website Kaggle by looking at the search results for "Football". I then found the individual players data for each season from 2020/21 to 2025/26 and used this. The link to the repository is attached below.

https://github.com/vaastav/Fantasy-Premier-League/tree/master/data

Description of data:

I focused on Fantasy Premier League (FPL) data covering six seasons of the English Premier League. In Fantasy Premier League, users build their own team using real players from the Premier League, with players earning or losing points based on their performances in real matches. For example, players can earn points for scoring goals and lose points for receiving a red card.

The dataset contains information on players from Premier League squads across the six seasons. It includes each player's total FPL points accumulated during each season, along with other information such as minutes played and yellow cards received.

I cleaned the dataset by removing players who recorded 0 minutes played during the season. I also added an additional column identifying which Premier League team each player played for, as this information was not included in the original dataset.

The cleaned dataset can be used to investigate patterns between the FPL points earned by players at a club and that same club's overall performance during the season. In particular, we can investigate whether teams whose players earn more FPL points tend to perform better in the Premier League and finish in a higher league position. As the dataset covers six seasons, these patterns can also be compared across different seasons.

Dataset suitability:

This dataset is suitable for the project because it contains FPL performance information for players across six Premier League seasons. The data includes each player's total FPL points, as well as other information such as minutes played and yellow cards. Having data from multiple seasons allows player performance to be compared across different teams and seasons. The additional team column I added also allows the player data to be grouped by club, which could be useful when investigating the relationship between FPL performance and team performance.

Limitations:

FPL points are based on specific individual actions and FPL scoring rules, so they do not directly represent how well a football team or individual player performs overall. Not every aspect of a player's performance is measured when calculating FPL points. For example, a player who covers a lot of distance, makes accurate passes and contributes to their team's ability to win may have a significant impact on the match but receive relatively few FPL points if they do not score, assist, or complete other actions that earn points. Therefore, FPL points may not fully reflect a player's overall contribution to their team. Players can also move between teams during a season, which could make comparisons between players and teams more difficult. Other factors that can affect a team's performance, such as injuries, transfers and changes in management, may also not be represented in the dataset.

Potential use in the project:

The FPL data could be used to investigate whether there is a relationship between the FPL points earned by players at a club and that club's overall Premier League performance. For example, the total FPL points earned by players at each club could be compared with the club's final league position in a particular season. This could help identify whether teams that perform better in the Premier League tend to have players who earn more FPL points.
