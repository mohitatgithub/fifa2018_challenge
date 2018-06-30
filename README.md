### FIFA Challenge

#### Introduction
This is notebook for Upgrad FIFA prediction challenge. we have used 4 datasets, 6 features & weighted average method to make naive predictions for round 16, quarter-finals, semi-finals & finals. visualization was done in tableau & remianing eda, data preprocessing & score calculation was done in R.  

#### Data Sources:

1. https://www.kaggle.com/tadhgfitzgerald/fifa-international-soccer-mens-ranking-1993now (fifa_ranking.csv)

2. https://www.kaggle.com/ahmedelnaggar/fifa-worldcup-2018-dataset (World Cup 2018 Dataset.csv)

3. https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017 (results.csv)

4. https://github.com/neaorin/PredictTheWorldCup/tree/master/input (matches.csv)

#### Feature Extraction & Weightage
We have calculated following key features from above datsets & given below weightages as per their relevance(subjective) for winner predictions.

Feature | Weightage
------------ | -------------
Previous Titles | 5%
Previous Finals | 10%
Previous Semifinals | 10%
Average Total Points | 25%
Average Lead | 25%
Average Rank | 25%

#### Predicted Winners:

*Round 16*

Teams | Winner
------------ | -------------
France vs Argentina | Argentina
Uruguay vs Porugal  | Porugal
Brazil vs Mexico | Brazil
Belgium vs Japan | Belgium
Spain vs Russia | Spain
Croatia vs Denmark | Croatia
Sweden vs Switzerland | Sweden
Columbia vs England | England


*Quarter-Finals*

Teams | Winner
------------ | -------------
Porugal vs Argentina | Argentina
Brazil vs Belgium | Brazil
Spain vs Croatia | Spain
Sweden vs England | England


*Semi-Finals*

Teams | Winner
------------ | -------------
Brazil vs Argentina | Brazil
Spain vs England | Spain


*Finals*

Teams | Winner
------------ | -------------
Spain vs Brazil | Brazil
