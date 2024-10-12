# NBA-Shots
Prediction of the probability of making a shot based on it's properties.

The dataset contains properties of the shots taken in the NBA regular season 2023-24. The following features are present:
1. SEASON_1: 2024
2. SEASON_2: 2023-24
3. TEAM_ID: ID of the team of the player who took the shot
4. TEAM_NAME: Name of the team of the player who took the shot
5. PLAYER_ID: ID of the player who took the shot
6. PLAYER_NAME: Name of the player who took the shot
7. POSITION_GROUP: Position group of the player who took the shot (G\F\C)
8. POSITION: Position of the player who took the shot [SG \ SF \ PG \ PF \ PF-SF \ C-PF \ C \ PF-C \ PG-SG \ SF-PF \ SG-PG \ SF-SG]
9. GAME_DATE: Date of the game
10. GAME_ID: ID of the game
11. HOME_TEAM: Home team of the game
12. AWAY_TEAM: Away team of the game
13. EVENT_TYPE: Made shot \ Missed shot
14. SHOT_MADE: True \ False
15. ACTION_TYPE: Type of the shot. For example: Step Back Jump Shot
16. SHOT_TYPE: 2 points or 3 points shot: 2PT Field Goal \ 3PT Field Goal
17. BASIC_ZONE: Name of the zone from where the shot was taken. For example: Restricted Area.
18. ZONE_NAME: Center \ Left Side Center \ Right Side Center \ Right Side \ Left Side \ Back Court
19. ZONE_ABB: C \ LC \ RC \ R \ L \ BC
20. ZONE_RANGE: THe range of the zone from which the shot was taken: 8-16 ft. \ 24+ ft. \ Less Than 8 ft. \ 16-24 ft. \ Back Court Shot
21. LOC_X: Location of the shot in X axis (-50 to 50 ft.)
22. LOC_Y Location of the shot in Y axis (-50 to 50 ft.)
23. SHOT_DISTANCE: Distance to the center of the hook
24. QUARTER: Number of the quarter in which the shot was taken
25. MINS_LEFT: Number of minutes left
26. SECS_LEFT: Number of seconds left


The main goal of this work is to predict the probability of making the shot based on the above mentioned properties.
Link to dataset in Kaggle: https://www.kaggle.com/datasets/mexwell/nba-shots

Machine learning algorithms used:
1. Logistic Regression
2. Naive Bayes classifier
3. K Nearest Neighbors
