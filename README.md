# scoutium_player_potential_prediction



![scout](https://github.com/Merttcoskun/scoutium_player_potential_prediction/assets/111244707/8dd043d8-bda0-4851-8b19-888316eefbe4)


<h3> Business Problems <h3>

Predicting which class (average, highlighted) players are based on the points given to the characteristics of the football players watched by the scouts.

<h3> Dataset Story <h3>

The data set consists of information containing the characteristics and scores of the football players evaluated by the scouts according to the characteristics of the football players observed in the matches from Scoutium.

- task_response_id: The set of a scout's evaluations of all players on a team's roster in a match
- match_id: The id of the corresponding match
- evaluator_id: The id of the evaluator (scout)
- player_id: The id of the respective player
- position_id: The id of the position that the relevant player played in that match (1=Goalkeeper, 2=Stopper, 3=Right back, 4=Left back, 5=Defensive midfielder, 6=Central midfielder, 7=Right wing, 8=Left wing, 9=Offensive midfielder, 10=Striker)
- analysis_id: The set of a scout's attribute evaluations of a player in a match
- attribute_id: The id of each attribute that players were evaluated for
- attribute_value: The value (points) given to a player's attribute by a scout
- potential_label: Label that indicates the final decision of a scout regarding a player's potential in a match (target variable)

