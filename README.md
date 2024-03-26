# Dota2 TI23 Draft Phase Analysis

![dota 2 banner](capsule_616x353.jpg)

## Context
For those who may not be familiar, Dota 2 is a multiplayer online battle arena (MOBA) video game developed and published by Valve Corporation. This games pits two teams of 5 players against each other in a race to destroy the opposing teams Ancient, a heavily guarded structure located within their base, while defending their own. Each player controls a powerful character known as a "hero," each with unique abilities and roles.
Dota 2 is one of the most prominent titles in the esports scene. It boasts a large player base and a thriving competitive scene with numerous tournaments, including Valve's flagship event, The International, which features the world's best teams competing for millions of dollars in prize money. The game's complex mechanics, deep strategy, and constant updates have contributed to its enduring popularity among both players and spectators in the esports community.

## Project Overview:

This Python data analysis project focuses on dissecting the draft phase data from all matches of the Dota 2 International 2023 tournament. Instead of scrutinizing team performances, the analysis delves into the matches at a hero level. During the draft phase of a game of dota 2 the two teams take turns banning heroes from being able to be used during the match by either team, and picking heroes for their team. Each team ends up banning 7 heroes and picking 5 heores, resulting in 24 heroes either getting picked or banned in a single match. Due to the deep complexity of dota 2's mechanics, the draft phase involves an incredible amount of strategy. Beyond just picking or banning heroes considered strong in the current version of the game, teams must also take in to consideration things like banning a hero that synergizes well with a hero the other team has already picked, banning heroes considered to be strong against a hero you want for your team, or even just banning a hero that a member of the opposing team is known fore being very good with.
This link provides a look at what the draft phase looks like for a high profile game dota:
https://youtu.be/33LZ9pUJr0o?t=4218
The primary objectives include:

### Frequency of Hero Picks/Bans:
Analyzing how often each hero is either picked or banned during the draft phase across all matches of the tournament.

### Impact of Picks/Bans on Victory:
Investigating the correlation between hero picks/bans and match outcomes, specifically assessing how frequently those picks or bans lead to a victory for the team that selected them.

## Methodology:
### Data Collection: 
Utilized official match data sources and APIs to collect comprehensive data on hero picks, bans, and match results from the Dota 2 International 2023 tournament.

### Data Analysis: 
Employed Python's data analysis libraries (e.g., pandas, numpy) to process and analyze the collected data. The analysis includes frequency distributions of hero picks/bans and their respective win rates.

## Results:
### Hero Frequency Analysis:
Provided insights into the most frequently picked and banned heroes throughout the tournament.
### Impact on Victory:
Examined the relationship between hero picks/bans and match outcomes, shedding light on which heroes significantly influenced match results.


