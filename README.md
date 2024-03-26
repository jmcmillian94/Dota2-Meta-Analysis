# Dota2 TI23 Draft Phase Analysis

![dota 2 banner](capsule_616x353.jpg)

## Context
For those who may not be familiar, Dota 2 is a multiplayer online battle arena (MOBA) video game developed and published by Valve Corporation. This games pits two teams of 5 players against each other in a race to destroy the opposing teams Ancient, a heavily guarded structure located within their base, while defending their own. Each player controls a powerful character known as a "hero," each with unique abilities and roles.

Dota 2 is one of the most prominent titles in the esports scene. It boasts a large player base and a thriving competitive scene with numerous tournaments, including Valve's flagship event, The International, which features the world's best teams competing for millions of dollars in prize money. The game's complex mechanics, deep strategy, and constant updates have contributed to its enduring popularity among both players and spectators in the esports community.

This Python data analysis project focuses on dissecting the draft phase data from all matches of the Dota 2 International 2023 tournament. Instead of scrutinizing team performances, the analysis delves into the matches at a hero level, analyzing how influential each hero was and the frequency at with the pro teams picked or banned them. 

During the draft phase of a Dota 2 match, each team alternates banning and picking heroes, resulting in a total of 24 heroes either picked or banned every match. This phase is characterized by strategic decision-making, extending beyond selecting heroes deemed poweful in the current patch to considering synergies, countering opponent picks, and neutralizing individual player strengths.

This link provides a look at what the draft phase looks like for a high profile game dota:
https://youtu.be/33LZ9pUJr0o?t=4218

And this is a link to the highlights of the International 2023, just for fun!
https://youtu.be/Rc92Gi4FwPY?t=15

## Project Overview:

The objective of this project was to identify the most influential heroes among the 124 available, analyzing their frequency of picks and bans across all tournament matches. Additionally, the project aimed to discern the correlation between these picks/bans and team victories, providing valuable insights into the pivotal roles played by specific heroes in competitive gameplay.

Utilizing the OpenDota API, I retrieved match data encompassing all 151 games of the International 2023 tournament. I isolated the draft data from each match, organizing it into a dataframe. This data serves as the foundation for constructing a tableau dashboard. Additionally, within the notebook, I've built several bar graph visualizations using Plotly, offering concise snapshots of findings derived from the dataset.

