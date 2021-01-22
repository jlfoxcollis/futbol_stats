##Games

```
###Games index
As a visitor

When I visit the games index page, I want to see All games ordered by season.
The game should be a clickable link that redirects to that games show page,
And the season should be a link redirecting to that seasons show page.
(note: This list of games should
```
 
### All games statistics
(note: these statistics are for all teams across all seasons/leagues.  An all time game stats page.)

```
As a visitor

When I visit the game statistics index page, I see the game with the highest total score(sum of the winning and losing teams scores).
```

```
As a visitor

When I visit the game stats index page, I see the game with the lowest total score(sum of the winning and losing teams scores).
```

```
As a visitor

When I visit the games stats index page, I see the percentage of games that a home team has won(rounded to nearest 100th).
```

```
As a visitor

When I visit the games stats index page, I see the percentage of games that a visitor has won(rounded to nearest 100th).
```

```
As a visitor

When I visit the games stats index page, I see the percentage of games that resulted in a tie(rounded to nearest 100th).
```

```
As a visitor

When I visit the games stats index page, I see A list of seasons with the count of games played during each season.
I also see the average number of goals scored in a game for that season.
Each season should be a clickable link that directs to that seasons show page.
```

```
As a visitor

When I visit the games stats index page, I see the average number of goals scored in a game across all seasons including home and away goals(rounded to nearest 100th).
```


### Games show page

```
As A visitor

When I visit a games show page, I should see that games statistics, including:
-season as link to that seasons show page
-both away/home teams names as link to respectice show pages
- away/home goals
-And venue
```

###League Statistics

```
Note:  With the provided CSV data, There is only 1 league which represents statistics across all seasons.
You can approach this as an index view, or you can create a league table, and setup the relationship that
A league can have many seasons, and a season belongs to a league.

As a visitor

When I visit the league statistics index/show page, I see the Following Statistics.
count_of_teams: Total number of teams in the data.
best_offense: Name of the team with the highest average number of goals scored per game across all seasons.
worst_offense: Name of the team with the lowest average number of goals scored per game across all seasons.
highest_scoring_visitor: Name of the team with the highest average score per game across all seasons when they are away.
highest_scoring_home_team: Name of the team with the highest average score per game across all seasons when they are home.
lowest_scoring_visitor: Name of the team with the lowest average score per game across all seasons when they are a visitor.
lowest_scoring_home_team: Name of the team with the lowest average score per game across all seasons when they are at home.

```

#Season

```
###Seasons index
As a visitor

When I visit the Seasons Index, I want to see the season, and the count of games in that season.
Each season should be a link to that seasons show page.
```

##Season Show Page/Statistics

``` 
As a visitor

When I visit a Season Statistics show page, I see the name of the Coach with the best win percentage for the season.
Next to the coaches name, should be his teams name as a clickable link to that teams show page.
```

```
As a visitor
When I visit a season show page, I see the name of the Coach with the worst win percentage for the season.
Next to the coaches name, should be his teams name as a clickable link to that teams show page.
```

```
As a visitor
When I visit a season show page, I see the name of the team with the best ratio of shots to goals for the season.
That teams name should be a clickable link to that teams show page.
```

```
As a visitor
When I visit a season show page, I see the name of the team with the worst ratio of shots to goals for the season.
That teams name should be a clickable link to that teams show page. 
```

```
As a visitor
When I visit a season show page, I see the name of the team with the most tackles for the season.
That teams name should be a clickable link to that teams show page.
```

```
As a visitor
When I visit a season show page, I see the name of the team with the fewest tackles for the season.
That teams name should be a clickable link to that teams show page.
```

```
As a visitor

```

##Team Statistics

```
#Team_info
As a visitor

When I visit a teams show page, I want to see that teams_info displayed.
```

```
#best_season
As a visitor

When I visit a teams show page, I want to see the name of that teams Best season.
(note: Best season is determined by the season with the highest win percentage for that team.)

I also want that season name to be a link that takes me to that seasons show page.
```

```
#worst_season
As a visitor

When I visit a teams show page, I want to see the name of that teams Worst season.
(note: Worst season is determined by the season with the lowest win percentage for that team.)

I also want that season name to be a link that takes me to that seasons show page.
```

```
#Average_win_percentage
As a visitor

When I visit a teams show page, I want to see the average win percentage of all games for that team.
```

```
#most_goals_scored
As a visitor

When I visit a teams show page, I want to see that teams most goals scored in a single game, 
including a link to that games show page.
```

```
#fewest_goals_scored
As a visitor

When I visit a teams show page, I want to see that teams fewest goals scored in a single game,
including a link to that games show page.
```

```
#favorite opponent
As a visitor

When I visit a teams show page, I want to see that teams favorite opponent.
(note: favorite opponent is the team that has the lowest win percentage against current team.)
That Opponents name should be a link that redirects to that teams show page.
```

```
#rival
As a visitor

When I visit a teams show page, I want to see that teams Rival!
(not: A rival is the team with the Highest win percentage against current team.)
The Rivals name should be a link that redirects to that teams show page.
```


