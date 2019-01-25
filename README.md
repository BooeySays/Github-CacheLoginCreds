# Github-CacheLoginCreds

A very simple script to help folks cache their
Github log in credentials so they don't have to
keep entering it when they go to push/pull their
repo.

INSTRUCTIONS:

I made two scripts for you guys - a fully automated
script, and for the control freak, a some what auto
(and guided) version.

NOTE:	Which ever version you run, the end results
		are going to be the same:
			1 - Run the commandto cache your crede-
			    ntials
			2 - Make a small edit to one of your repo
			    file - README.md
			3 - Add the file, commit it, and push it
			4 - Trigger the login prompt and enter 
			    your USERNAME AND PASSWORD for one
				last time..
			5 - Undo the changes to your dummy file.
			6 - Add it, commit it, and push it.

		Git should have puhed your repo with out asking
		you for your password.


Method 1 - Automatic
	
	To set everything up using the automatic method, go
to where you cloned/downloaded this repo's files and run:
,,,,
. ./cachemycreds-auto.sh
,,,,
