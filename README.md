# PUBG-data-analysis

This is the Pubg Analysis which explores the game features and players preferences. A complete Preprocessing is done on the Data, Removed Outliers using IQR and dropped Null Values

We have two datasets which explains PUBG in different perspectives.The first one is the Aggregate data where columns are match_mode, party_size, player_assists, player_dbno, player_dist_ride, player_dist_walk, player_dmg, player_kills.

The another dataset we have is Kill Data which contains the players kill position, victim position, placement_rate, team_id, player_mode, game_size, party_size.

Explaining every column for Aggregate and the type of data it has:-

1.   **date**-Start time of the game- Nominal
2.   **game_size**-size of the game map-Discrete
3.    **match_id**	Event Unique ID	Nominal
4.    **match_mode**	Game Mode (First/Third Person View)	Nominal
5.    **party_size**	Squad size (1 person/2 people/4 people)	Discrete
6.    **player_assists**	Rescue teammates	Discrete
7.    **player_dbno**	Number of times the player was knocked down	Discrete
8.    **player_dist_ride**	Driving Distance	Continuous
9.    **player_dist_walk**	Walking distance	Continuous
10.   **player_dmg**	Injury points	Discrete
11.   **player_kills**	kills	Discrete
12.   **player_name**	Player Game id	Nominal
13.   **player_survive_time**	Player survival time	Continuous
14.   **team_id**	The player’s team number	Discrete
15.  **team_placement**	The final ranking of the player’s team	Discrete


Explaining every Column for Kill and the type of data it has:-

1. **killed_by**-Which weapon is killed-Nominal
2. **killer_name**-Killer game id-Nominal
3. **killer_placement**-The final ranking of the team where the killer is located-Discrete
4. **killer_position_x**-X coordinate of the killer when the killing behavior occurs-Continuous
5. **killer_position_y**-The Y coordinate of the killer when the killing behavior occurs-Continuous
6. **map**-Game Map (ERANGEL ISLAND/MIRAMAR DESERT)-Nominal
7. **match_id**-Event Unique ID-Nominal
8. **time**-When the kill occurs (how many seconds after the game starts)-Discrete
9. **victim_name**-The killed game id-Nominal
10. **victim_placement**-The final ranking of the team where the killer is located-Discrete
11. **victim_position_x**-X coordinate of the person being killed when the killing occurs-Continuous
12. **victim_position_y**-The Y coordinate of the killer at the time of the killing behavior-Continuous
