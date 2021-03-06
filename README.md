### FIFA Challenge

#### Introduction
This is repository for Upgrad FIFA prediction challenge. we have used 4 datasets, 6 features & weighted average method to make naive predictions for round 16, quarter-finals, semi-finals & finals. visualization was done in tableau & remaining EDA, data preprocessing & score calculation was done in R. Check code for further clarification on any of below steps.

#### Data Sources:

1. https://www.kaggle.com/tadhgfitzgerald/fifa-international-soccer-mens-ranking-1993now (fifa_ranking.csv)

2. https://www.kaggle.com/ahmedelnaggar/fifa-worldcup-2018-dataset (World Cup 2018 Dataset.csv)

3. https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017 (results.csv)

4. https://github.com/neaorin/PredictTheWorldCup/tree/master/input (matches.csv)

#### Feature Extraction & Weightage:
We have calculated following key features from above datasets & given below weightages as per their relevance(subjective) for winner predictions. these features were further normalized on scale of 1 to 10 before taking weighted average.

Feature | Weightage
------------ | -------------
Previous Titles | 5%
Previous Finals | 10%
Previous Semifinals | 10%
Average Total Points | 25%
Average Lead | 25%
Average Rank(Inversed) | 25%

Finally feature WinChance was calculated as weighted sum of above 6 features. Final values of WinChance are given in final_dataset.csv in output folder.

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

#### Notes:
1. Code file written in R Markdown file is saved in Code folder.
2. All datasets used are saved in input folder.
3. Final Code output in html & pdf is saved in output folder. final dataset used for predictions is also stored in output folder as 'final_dataset.csv'.

_Due to lack of time we have not used any ML algorithm to make prediction, rather we have used a weighted average on normalized feature values to make a slightly better guess then a toss of coin. We are still working on solution locally & will include ML algorithms & better features to make predictions in future solutions._
