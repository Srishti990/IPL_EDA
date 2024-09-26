# IPL Data Analysis

This repository contains an analysis of Indian Premier League (IPL) data, utilizing two datasets: matches and deliveries. The analysis aims to provide insights into team performances, player statistics, and the influence of various match conditions on outcomes.

## Datasets

### 1. Matches Dataset

This dataset includes details about each IPL match with the following columns:

| Column            | Description                                             |
|-------------------|---------------------------------------------------------|
| `id`              | Unique identifier for each match                       |
| `season`          | Season of the IPL                                      |
| `city`            | City where the match was played                        |
| `date`            | Date of the match                                      |
| `match_type`      | Type of match (e.g., league, playoff)                 |
| `player_of_match` | Player awarded for outstanding performance              |
| `venue`           | Venue where the match took place                       |
| `team1`           | First team participating in the match                  |
| `team2`           | Second team participating in the match                 |
| `toss_winner`     | Team that won the toss                                 |
| `toss_decision`   | Decision made by the toss winner (bat/bowl)           |
| `winner`          | Team that won the match                                |
| `result`          | Result of the match (win/loss/no result)               |
| `result_margin`   | Margin of victory (runs/wickets)                      |
| `target_runs`     | Runs required to win (if applicable)                  |
| `target_overs`    | Overs to achieve the target (if applicable)           |
| `super_over`      | Indicates if a super over was played                   |
| `method`          | Method of match completion (e.g., rain)               |
| `umpire1`        | Name of the first umpire                               |
| `umpire2`        | Name of the second umpire                              |

### 2. Deliveries Dataset

This dataset provides details about each delivery in the matches, with the following columns:

| Column              | Description                                          |
|---------------------|------------------------------------------------------|
| `match_id`          | Unique identifier for the match                      |
| `inning`            | Inning number (1 or 2)                              |
| `batting_team`      | Team that is batting                                 |
| `bowling_team`      | Team that is bowling                                 |
| `over`              | Over number                                         |
| `ball`              | Ball number within the over                         |
| `batter`            | Batter facing the delivery                           |
| `bowler`            | Bowler delivering the ball                           |
| `non_striker`       | Non-striker at the other end of the pitch           |
| `batsman_runs`      | Runs scored by the batsman                           |
| `extra_runs`        | Extra runs awarded (wides, no balls, etc.)         |
| `total_runs`        | Total runs scored on that delivery                   |
| `extras_type`       | Type of extra runs (e.g., bye, leg-bye, etc.)      |
| `is_wicket`         | Indicates if a wicket fell on that delivery         |
| `player_dismissed`  | Player who got out (if any)                         |
| `dismissal_kind`    | Kind of dismissal (e.g., bowled, caught)            |
| `fielder`           | Fielder involved in the dismissal                    |

## Libraries Used

- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Seaborn**: For enhanced visualizations.

## Analysis Insights

The following insights were derived from the analysis:

1. **Number of Matches in Each Season**: A breakdown of the total matches played per IPL season.
2. **Number of Matches Won by Each Team**: Insights into the performance of each team in terms of wins.
3. **Impact of Toss Decision on Match Outcomes**: An analysis of how the toss decision affects match results.
4. **Most IPL Seasons Won by Teams**: Identification of teams with the highest number of season wins.
5. **Individual Statistics**:
   - Top boundary hitters
   - Top 10 players awarded "Player of the Match"
   - Top venues based on match statistics
   - Top batsmen and bowlers based on performance metrics
