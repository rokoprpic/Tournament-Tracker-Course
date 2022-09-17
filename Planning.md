### Scenario 
Tournament tracker where people play set of games to determine top player. 
Idea is to create tournament bracket system which will tell player who to play.
At the end winner should ne identified.

###  Requirments
1. Track games played and their outcome
2. Multiple competitors play in tournament
3. Create tournament plan (who plays who)
4. Schedule games
5. Single lose eliminates a player
6. The last player standing is the winner

##### Questions about project ???
- how many player, order of player random, schedule of game
- can games be played simultaneously, does system need to store scores
- type of frontend ( form, webpage, app .. ), where to store data
- type of reporting, levels of access

##### Requirment extended
- variable number of players, ordering is random, games aren't scheduled, each round is completed before another begins
- store score for each player, desktop app (later webapp), data is tored in SQL server (or txt file)
- reporting specifing the outcome (form, email etc), anyone using the app can fill the game score
- system shouuld notify via email

### Big Picture
- Structure : Windows Form app and Class Library
- Data : SQL and/or Text File
- Users : One at a time on one application
- Key Concepts : Email, SQL, Custom Events, Error Handling, Interfaces, Radnom Ordering, Texting, 



