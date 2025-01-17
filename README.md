# 2021Fall_finals

Project Title: Exploratory Data Analysis of Indian Premier League.

Background: Indian Premier League also known as IPL is a professional cricket tournament hosted in India where players from multiple international teams participate. There are 8 teams competing over 200 players participating each year and around 60 matches played. As IPL is a cash-rich tournament, multiple factors need to be considered while analyzing players’ performance.

![image](https://user-images.githubusercontent.com/87818442/144640653-e1185de0-3331-4423-abc4-4779a081dc27.png)

Potential Hypothesis:

1. Event of winning the toss is positively correlated with the event of a team winning the game.

2. Fast bowlers are more effective than spinners during death overs. (Death over – Last 4 overs of the innings)

3. Players aged 35 or more have a lesser impact on the game as compared to younger players.

4. Teams with orange or purple cap holder has a higher chance of winning the tournament. (Orange cap – player with highest runs in the tournament, purple cap – player with highest wickets in the tournament)

Future Scope: 

1. If the top 3 players score more than 60 runs in powerplay (powerplay means the first 6 overs) or bowlers take 3 or more wickets inside the powerplay then the team has a 75% chance of winning the game.

2. Players that sell for a higher price in the auction do not perform well in the tournament.

We are considering IPL datasets from the year 2008 to 2017.

IPL Dataset Till 2017: https://data.world/raghu543/ipl-data-till-2017

IPL Auction Datasets: We referred to the auction dataset from 2008 to 2017 from this dataset. https://github.com/Foridur3210/IPL-Dataset-Player-price-prediction/blob/master/IPL%20IMB381IPL2013.csv#L113
We also created an auction dataset manually by referencing https://www.iplt20.com/auction

IPL Auction Additional Reference: We are even trying to the latest auction prices from the official IPL website, and we will use this in our dataset. We will be referring auction prices from 2013 to 2017 from this dataset. 

Contributions:

Parth Sangvhi (parthss4) : Hypothesis 1 & 2
Sunny Solanki (solanki6) : Hypothesis 3 & functions for hypothesis 4
Megh Shah (megh2): Hypothesis 4

Each hypothesis consisted of functions mentioned in functions.py file as well as visualizations mentioned in jupyter notebook. Doctests were added in the .py file itself.