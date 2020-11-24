# NBA_scraping_analysis
You can find the full data sets that I scraped, my analysis and others on [Kaggle Profile](https://www.kaggle.com/jacobbaruch)
1. [Player of the week](#1-player-of-the-week)
2. [Head Coaches](#2-head-coaches)
3. [Basketball Players Statistics per Season](#3-Basketball-Players-Statistics-per-Season)

## 1. Player of the week 
[Kaggle Dataset](https://www.kaggle.com/jacobbaruch/nba-player-of-the-week)
* Scraping award data at seasons 1979-80 to 2019-20.
* Analysis award behavior

#### Info

 | Parameter |	Description	|
 | --- | --- |
 | Age| |
 | Conference | |
 | Date | |
 | Draft Year | |
 | Height | Feet / CM |
 | Player | |
 | Position | |
 | Season | |
 | Season Short | |
 | Weight | Pounds / KG|
 | Real Value | If two awards given [east & west] on the same week the player gets 0.5 point else gets 1 point |

## 2. Head Coaches 
[Kaggle Dataset](https://www.kaggle.com/jacobbaruch/nba-head-coaches)
### A.Historical NBA Head Coaches
 Scraping info about head coaches, starting from 1947

 #### Info

  | Parameter |	Description	|
  | --- | --- |
  | Birth date| dd-mmm-yyyy|
  | End season | for example 2017-2018 |
  | Name | |
  | Nationality | |
  | Start season | for example 2017-2018|
  | Teams | |
  | Start season short | for example 2017|
  | End season short | for example 2017|
  | Num of teams | |
 
### B.NBA Coach of the Year Recipients
 Scraping info about NBA coach of the year, starting from 1963

 #### Parameters

  | Parameter |	Description	|
  | --- | --- |
  | Year |	starting year of Season	|
  | Coach |	Head Coach Name|
  | Team | |
  | W-L | W-L in Season |
  | Playoffs W-L | Playoffs W-L in Season |
  | Career W-L | Career W-L in Season |
  | Exp (Years) | Experience Years till season |
  | W | wins in Season |  
  | L | losses in Season |
  | Playoffs W | Playoffs wins in Season|
  | Playoffs L | Playoffs losses in Season |
  | Career W | Careers wins till Season|
  | Career L | Careers losses till Season|
  | Born | Birthdate MMM DD, YYYY|
  | Birthplace | |
  | College | |
  | Overall Record | Career Overall Record |
  
## 3. Basketball Players Statistics per Season
[Kaggle Dataset](https://www.kaggle.com/jacobbaruch/basketball-players-stats-per-season-49-leagues)
* Scraping player statistics & details per season of 49 League and ~11K players (2010 - 2020)

**output files** 
 1. players_stats_by_season.csv - player statistics per season
 2. players_stats_by_season_full_details.csv - players statistics per season + details 
 
 #### Info

  | Parameter |	Description	| players_stats_by_season | players_stats_by_season_full_details |
  | --- | --- | --- | --- |
  | Season | yyyy - yyyy | v | v |
  | Stage | International, NBA: Playoffs, Regular_Season | v | v |
  | Player | Player Full Name | v | v |
  | Team | Team Name | v | v |
  | GP | # Games Played | v | v |
  | MIN | # Minutes Played | v | v |
  | FGM | # Field Goals Made | v | v |
  | FGA | # Field Goals Attempts | v | v |
  | 3PM | # Three Points Made | v | v |
  | 3PA | # Three Points Attempts | v | v |
  | FTM | # Free Throws Made | v | v |
  | FTA | # Free Throws Attempts | v | v |
  | TOV | # Turnovers | v | v |
  | PF | # Personal Fouls | v | v |
  | ORB | # Offensive Rebounds | v | v |
  | DRB | # Defensive Rebounds | v | v |
  | REB | # Rebounds | v | v |
  | AST | # Assists | v | v |
  | STL | # Steals | v | v |
  | BLK | # Blocks | v | v |
  | PTS | # Points | v | v |
  | birth_year | Birth Year |  | v |
  | birth_month | Birth Month |  | v |
  | birth_date | Birth Date |  | v |
  | height | Height [Feet] |  | v |
  | height_cm | Height [CM] |  | v |
  | weight | Weight [Pounds] |  | v |
  | weight_kg | Weight [KG] |  | v |
  | nationality | Nationality |  | v |
  | high_school | High School |  | v |
  | draft_round | Draft Round | | v |
  | draft_pick | Draft Pick | | v |
  | draft_team | Draft Team | | v |
  

  
# Acknowledgements

Player of the week - scraped from [basketball real GM](https://basketball.realgm.com/)

Historical NBA Head Coaches- scraped from [basketball real GM](https://basketball.realgm.com/nba/staff-members/20/Head-Coach/Historical)

NBA Coach of the Year Recipients - scraped from [espn](http://www.espn.com/nba/history/awards/_/id/34)

Basketball Players Statistics per Season - scraped from [basketball real GM](https://basketball.realgm.com/)
