# TODO LIST #

>A list of things todo!

## General ##

- [ ] Make a todo list
- [ ] Complete tasks on todo list

## Directory Specific ##

-[ ] bin
  -[ ] Make this folder
  -[ ] Create bin/install.pl script. This should be a wrapper for GenericLeaderboard->install()
  -[ ] Create bin/upgrade.pl script. This should be a wrapper for GenericLeaderboard->upgrade()

### cgi ###

-[ ] Segregate private methods inside here to lib/GenericLeaderboard.pm as helper methods
-[ ] Make database settings configrable, possibly located in lib/config.pm
-[ ] Do lookup on conf table for app_title and display that in header
-[ ] Create POD for cgi/leaderboard file
-[ ] List out cpan modules that cgi/leaderboard file depends on

#### Step Specific ####

-[ ] main
  -[x] Start coding on this
  -[ ] Come up with acceptance criteria
    -[ ] Check aliases and use those instead when listing ranks
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] settings
  -[ ] Start coding on this
  -[ ] Acceptance criteria
    -[ ] Allow app title to be set, defaults to "GenericLeaderboard"
    -[ ] Set alias for "map"
    -[ ] Set alias for "map_group"
    -[ ] Set alias for "round"
    -[ ] Set alias for "round_group"
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] add_map
  -[ ] Start coding on this
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] add_map_group
  -[ ] Start coding on this
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] add_team
  -[x] Start coding on this
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] add_player
  -[x] Start coding on this
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] add_player_team
  -[ ] Start coding on this
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] add_round
  -[ ] Start coding on this
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] add_round_group
  -[ ] Start coding on this
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] add_score
  -[x] Start coding on this
  -[ ] Move (rename) this to add_round_score
-[ ] add_round_score
  -[ ] Start coding on this
  -[ ] Take add_score and move (rename) it to this step
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] add_round_group_score
  -[ ] Start coding on this
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] install
  -[x] Start coding on this
  -[ ] Segregate functionality of this step to lib/GenericLeaderboard.pm
  -[ ] Create bin/install.pl script
  -[ ] Remove this step
-[ ] search
  -[x] Start coding on this
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] titles
  -[x] Start coding on this
  -[ ] Come up with acceptance criteria
  -[x] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria
-[ ] achievements
  -[ ] Start coding on this
  -[ ] Come up with acceptance criteria
  -[ ] Finish coding this out
  -[ ] Add POD for this method
  -[ ] Review acceptance criteria

### lib ###

-[ ] Make this folder
-[ ] Make lib/GenericLeaderboard.pm file
-[ ] Segregate private methods inside cgi/leaderboard as helper methods in here
-[ ] Move install step from cgi/leaderboard to here
-[ ] Install method needs to insert initial records into team table
-[ ] Create upgrade method
-[ ] Create POD for lib/GenericLeaderboard.pm file
-[ ] List out cpan modules that lib/GenericLeaderboard.pm file depends on

### media ###

-[x] Make media/style.css file

### tt ###

-[ ] Add navigation to the following steps once completed
  -[ ] add_player
  -[ ] add_score

### t ###

-[ ] Make this folder
-[ ] Write unit tests for lib/GenericLeaderboard.pm file

## Databases ##

-[ ] Create foreign key constraints
-[ ] Create alias records inside conf table
  -[ ] App Title (currently "GenericLeaderboard" is hard-coded in)
  -[ ] "map" (could be something like "track")
  -[ ] "map_group" (could be something like "circuit")
  -[ ] "round" (could be something like "race")
  -[ ] "round_group" (could be something like "session")


