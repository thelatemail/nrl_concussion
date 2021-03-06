# NRL concussion
Crowd-sourced data on concussion tests in NRL (Australian National Rugby League), 2014 - 2019 currently.

This is not an exhaustive list, and validated only against media reports, contemporaneous Twitter posts, or no-longer accessible video footage removed from YouTube. It is in no way official data or endorsed by the NRL in any way.

Two files are included:

- **nrl_conc_main.csv**  
The main file which has the following columns:  
eventid - the primary key for linking other datasets  
year - season/year of the game  
round - round within a season  
date - date (mmm-dd)  
team1 - abbreviation of team 1  
team2 - abbreviation of team 2  
player - player name (only surname for later years currently)  
twitter_time - timestamp from Twitter post if relevant  
returned - passed concussion test and/or returned to game  
event_minute - clock minute within game when initial event occurred  

- **nrl_conc_sources.csv**  
eventid - the primary key for linking other datasets  
twitter_time - timestamp from Twiter post if relevant  
rec_nr - record number for source or comment  
comment - source url or comment  


## Possible sources for further validation/identification of cases:
NRL match replays - https://www.nrl.com/news/topic/match-replays  
NRL game reports (search for 'HIA' to find minute/player for interchanges) - https://www.nrl.com/draw/nrl-premiership/2016
