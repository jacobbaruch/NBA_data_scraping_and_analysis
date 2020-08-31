# NBA_scraping_analysis
You can find the full data sets that I scraped, my analysis and others on [Kaggle Profile](https://www.kaggle.com/jacobbaruch)
1. [Player of the week](#1-player-of-the-week)
2. [Head Coaches](#2-head-coaches)

## 1. Player of the week 
[Kaggle Dataset](https://www.kaggle.com/jacobbaruch/nba-player-of-the-week)
* Scraping award data at seasons 1979-80 to 2019-20.
* Analysis award behavior

#### Parameters

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

 #### Parameters

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
  
# Acknowledgements

Player of the week - scraped from [basketball real GM](https://basketball.realgm.com/)

Historical NBA Head Coaches- scraped from [basketball real GM](https://basketball.realgm.com/nba/staff-members/20/Head-Coach/Historical)

NBA Coach of the Year Recipients - scraped from [espn](http://www.espn.com/nba/history/awards/_/id/34)
