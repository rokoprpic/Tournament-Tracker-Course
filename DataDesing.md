### Mapping the Data

1. Team
* TeamMembers (List<Person>)
* TeamName (string)

2. Person
* FirstName (string)
* LastName (string)
* EmailAddress (string)
* CellPhoneNumber (string)
 
3. Tournament
* TournamentName (string)
* EntryFee (decimal)
* EnteredTeams (List<Team>)
* Prizes (Lsit<Prize>)
* Rounds (List<List<Matchup>>)

4. Prie
* PrizeNumber (int)
* PlaceName (string)
* PrizeAmount (decimal)
* PrizePercentage (double)

5. Matchup
* Entries (List<MatchupEntry>)
* Winner (Team)
* MatchupRound (int)

6. MatchupEntry
* TeamCompeting (Team)
* Score (double)
* ParentMatchup (Matchup)
