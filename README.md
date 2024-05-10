# Description

We have caught all the play_by_play happening during a NBA game so we have a flow of data and we want to create a nice array of hash which will sum everything.

Create a function analyse_nba_game(play_by_play_moves) which receives an array of play and will return a dictionary summary of the game.

Each play follow this format:



# Task

Create a print_nba_game_stats(team_dict) function which will a dictionary with name and players_data will print it with the following format (each column is separated by a tabulation (' ')):

HEADER
FOR PLAYER IN PLAYERS
PLAYER
TOTAL
Example 00

Players	FG	FGA	FG%	3P	3PA	3P%	FT	FTA	FT%	ORB	DRB	TRB	AST	STL	BLK	TOV	PF	PTS
Player00	XX	XX	.XXX	X	XX	.XXX	XX	XX	.XXX	XX	XX	XX	XX	X	X	XX	XX	XX
Totals	XX	XX	.XXX	X	XX	.XXX	XX	XX	.XXX	XX	XX	XX	XX	X	X	XX	XX	XX
Example 01

Players	FG	FGA	FG%	3P	3PA	3P%	FT	FTA	FT%	ORB	DRB	TRB	AST	STL	BLK	TOV	PF	PTS
Kevin Durant	9	21	.429	0	5	.000	9	10	.900	1	7	8	6	1	1	3	4	27
Stephen Curry	11	20	.550	5	9	.556	5	5	1.000	0	8	8	9	1	0	3	4	32
Klay Thompson	5	20	.250	1	8	.125	3	3	1.000	1	3	4	0	0	0	2	3	14
Draymond Green	1	6	.167	0	1	.000	0	0		1	12	13	5	3	0	6	3	2
Damian Jones	6	7	.857	0	0		0	0		2	1	3	2	0	3	2	4	12
Kevon Looney	5	11	.455	0	0		0	0		8	2	10	2	1	2	1	4	10
Shaun Livingston	3	5	.600	0	0		0	0		2	1	3	1	1	0	1	2	6
Quinn Cook	1	2	.500	1	1	1.000	0	0		1	1	2	1	0	0	2	2	3
Andre Iguodala	1	2	.500	0	1	.000	0	0		0	2	2	2	0	0	0	0	2
Jordan Bell	0	0		0	0		0	0		1	1	2	0	0	1	0	1	0
Jonas Jerebko	0	0		0	0		0	0		0	3	3	0	0	0	1	2	0	0
Alfonzo McKinnie	0	1	.000	0	1	.000	0	0		0	0	0	0	0	0	0	0	0
Team Totals	42	95	.442	7	26	.269	17	18	.944	17	41	58	28	7	7	21	29	108

# Install & Usage

pip install pandas

python my_nba_game_analysis.py