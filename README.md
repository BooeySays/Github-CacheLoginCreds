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

#	
#	  Head over to where ever you downloaded this
#    repo and run the script - cachemycreds.sh.
#
#	  The script will set everything up so that the
#	next time you enter your usernme and password,
#	it will get cached, and you will never have to
#	log in to your guthub to push or pull your repo
#	agan.
#
#	That said, you will need to trigger Git to ask
#	you for your usename and password one last time
#	after the scipt is done. So head over to one of
#	your Github repos after you run the script, pr-
#	eferabally one where you know will make you sign
#	in ( like  private one ).
#
#	Now, the easiest way that I've found to trigger
#	Git's login prompt, is to edit a file ( like the
#	README.md ), add a line to the end of the file,
#	git add the file, commit it, and then push the
#	repo.
#
#	Hopefully, you'll have to sign in. After you log-
#	ged in and git pushed the file, you can edit the
#	file again, remove the line, or whatever was added,
#	add, commit, and push everything again.
#
#	If everything went well, Git would have updated the
#	repo without asking you to log in.
#
