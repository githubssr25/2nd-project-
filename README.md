Analysis of NBA related data 

I will be using 538's database on their model for player evaluation called RAPTOR 
You can read more about it here: https://fivethirtyeight.com/features/how-our-raptor-metric-works/

Some areas I have started to look at and will continue to do so

1) How well does regular season performance predict player performance 

2) How do players offensive and defensive values change over time(ie 20-30 years)?

3) What defines certain positions? What kind of statistical traits? Can we help predict or define what a player's true position is based off certain statistical attributes?

4) The value of on/off data vs box score priors in evaluating players measured impact. 

Some classification or regression models used in this include KMeans Clustering, Random forest, KNN and Logistic regression. 


Unfortunately while they do list the components that go into the metric they do not publicly reveal how the data is computed unlike other pubilcly available metrics for NBA player evaluation such as PIPM
I do however think that there are alot of interesting things about the model which is why I used it. One thing you will find with this model you wont find with other publicly available metrics for evaluating players is the degree to which they use player tracking data. Player tracking data started to really become public in 2014 with the advancements in second spectrum cameras and means the model will incorporate components such as how much distance a player travels in a certain game, 
I do think it is absolutely fair to ask just how much some of these areas included in the metric actually are relevant to predicting player value, does traveling more distance for example really help evaluate player performance towards their contributions to help a team win? But regardless that's an aside.

