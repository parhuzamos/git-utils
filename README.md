git-utils
=========

Utilities for every day git tasks.

## gcm - Git Checkout Master
	Fetches and checks out the master, "totally" updating submodules too.
	
## gsu - Git Submodule Update
	"Totally" updates submodules corresponding to the main repo. Should _not_ be used after "gcm".
	
## gnew - Git New branch
	Create a new branch for a new task. Takes the current HEAD, use "gcm" to create from master.
	New branches are created in submodules too.