# :soccer: Optimal Soccer Team Selection and Analysis

__Project Version__: Version 1.0 :computer:
> Analyze real soccer teams and understand what are the factors that make them the best?

## About the project!
Sports data analytics is a very dynamic data problem with multiple variables that influence the game winning or losing chances. At a player level, physical and mental attributes of a player as well as his way around the ball affects his performance. At a team level, the level of funding, player composition and many other factors impact analytical predictions. This project aims to dive into a few of the important metrics that are crucial in soccer team analytics and provide insights. 

## Technologies
![Python](https://img.shields.io/static/v1?style=for-the-badge&message=Python&color=3776AB&logo=Python&logoColor=FFFFFF&label=)
![MongoDB](https://img.shields.io/static/v1?style=for-the-badge&message=MongoDB&color=47A248&logo=MongoDB&logoColor=FFFFFF&label=)
![Google Cloud](https://img.shields.io/static/v1?style=for-the-badge&message=Google+Cloud&color=4285F4&logo=Google+Cloud&logoColor=FFFFFF&label=)
![Apache Spark](https://img.shields.io/static/v1?style=for-the-badge&message=Apache+Spark&color=E25A1C&logo=Apache+Spark&logoColor=FFFFFF&label=)

## Features of the project :star:

- To crawl the data from website sofifa.com:

```
scrapy crawl spidy
```

- For performance statistics of 2 soccer teams: 

```
spark-submit --packages org.mongodb.spark:mongo-spark-connector_2.11:2.4.1 team_attack_defensive.py 'Real Madrid' 'FC Barcelona'
```
- Goals scored from various playes for each league

```
spark-submit --packages org.mongodb.spark:mongo-spark-connector_2.11:2.4.1 outside_inside_box.py
```

- For identifying a potential replacement for a player:

```
spark-submit --packages org.mongodb.spark:mongo-spark-connector_2.11:2.4.1 wage_calculator.py
```

- Understanding aggressiveness in teams in each league:

```
spark-submit --packages org.mongodb.spark:mongo-spark-connector_2.11:2.4.1 aggressiveness_in_teams.py
```

- Calculate average goals scored by each league over the years

```
spark-submit --packages org.mongodb.spark:mongo-spark-connector_2.11:2.4.1 average_goals_scored.py
```

- Correlating various player attributes:

```
spark-submit --packages org.mongodb.spark:mongo-spark-connector_2.11:2.4.1 correlation_features.py
```
- Suggesting a player replacement:

```
spark-submit --packages org.mongodb.spark:mongo-spark-connector_2.11:2.4.1 player_replacement.py 'B Matuidi'
```

## Future work :rocket:
TODOs for future development
* Reinforcement Learning: Identifying player positions and predicting the movement of ball
* Choosing your own ultimate team

## Status
_in progress_ :construction:

## Contact
Created by [@jediXNavi](https://github.com/jediXNavi) - feel free to contact me!