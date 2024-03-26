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

## Installation

1. Clone the repository
Using git bash navigate to a directory that you would like to store the repo and enter this into your git bash terminal:
```
git clone https://github.com/jmcmillian94/Dota2-TI23-Draft-Phase-Analysis
```
2. Setup a virtual enviornment
while still in the project directory enter this into your git bash terminal:
```
python -m venv venv
```
this will create a new virtual enviornment called venv inside your repo folder
   
3. activate the virtual enviornment
while still in the project directory enter this command into you git bash terminal:
```
source .venv/Scripts/activate
```
you should see a '(venv.)' appear above you command line in the git bash terminal

4. Install the required libraries
while the virtual enviornment is active enter this command in the git bash terminal:
```
pip install -r requirements.txt
```
This will install all of the packages included in the requirements.txt file to mimic the enviornment that I created the project in

5. With all of that done you can now open the Dota2 TI23 Draft Phase Analysis.ipynb file and execute the code. The code should create a 'draft_data.xlsx' file in the project file and also create two bar graphs, one for hero pick rate and one for hero ban rate. Remember that wehn you are finished you will need to deactivate the virtual enviornment using this comand in git bash:
```
deactivate
```

## Data Analysis Capstone Features Used
1. Read TWO data sets in with an API (or use two different APIs that have data you can combine to answer new
2. Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.
3. Make a Tableau dashboard
4. Utilize a virtual environment and include instructions in your README on how the user should set one up
5. Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don’t have any empty cells or incomplete cells that don’t do anything. Make sure it’s all functional before your final github commit.
