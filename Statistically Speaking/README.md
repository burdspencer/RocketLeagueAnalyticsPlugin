### Introduction ###

This project still doesn't have a proper name, so I'm going to call it RL Analytics Plugin, maybe give it a cool code name like Phoenix or something someday.

### Goals ###

In the coarse, long-term, I want this plugin to be able to log Rocket League stats in real-time for the purpose of someday analyzing them, be it in SQL or Python or R or what-have-you. To accomplish this, I'm likely going to be calling upon the existing knowledge present in the plugins 'Statistically Speaking' by Haltepunkt (found here https://bakkesplugins.com/plugins/view/58 and here https://github.com/haltepunkt/StatisticallySpeaking) and MatchOdds by Civilian360 (found here https://bakkesplugins.com/plugins/view/176 and here https://github.com/Davek84/MatchOdds)

### Road Map ###
To accomplish this goal, several things will need to happen first:
1. Take the file logging logic from Statistically Speaking and adapt it to be used by the real-time stat event capturing logic in MatchOdds.
  -Possibly could even keep the odds/MMR calculation as an extra stat to be logged.
2. Create logic to preserve data integrity and in turn, raise data quality
3. Create a log format that is both efficient and readable/usable, the data is no use to anyone if it's buggy and sparse.
