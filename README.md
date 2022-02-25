# Chess-Federation-Data-Base
Data Base will store:
- Tournaments 
- Olympiads
- Their squad, location
- Tours, player pairs, games 

There's going to be several roles:
- Guest
- User
- Player
- Manager
- Admin

**About roles**:
  - "Guest" can sign in / sign up to profile as User, Player, Manager, Admin. Guest can watch basic information like: players information, planned soonest tournaments, current games.
  - "User" can do application to create Player profile or for confirmation of Player role. User can everything that Guest do and, additionaly, add players profiles, tournaments to favourites. Also, User can publish his own events and invite another Users, Players.
  - "Player" is advanced User role. People who have Player role are written in separate database which store all activity information of players. These people have chess raiting which defines strength of player. Players can do application to take part in official tournaments with rating accounting, can do request to review the game for foul play, for banning Player.
  - "Manager" can create official tournaments, do application for canceling the tournament, invite Players (sometimes Users) for this tournaments, confirm/reject applications for taking part in, kick participants, update information. Manager can consider requests of unfair play, incorrect result of game.
  - "Admin" can change role of profiles if it's not Guest, delete/ban profiles.
