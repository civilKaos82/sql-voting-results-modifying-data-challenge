# Poll Db 2 Modifying Data 
 
##Learning Competencies 

##Summary 

 You've had a lot of practice querying the database with SQLtutor and other previous challenges, but here we'll actually change a database.  We'll continue working with the Poll Database.  

Download the database [here](https://github.com/downloads/dbc-challenges/binary_store/congress_poll_results.db), and open it up with `sqlite3 congress_poll_results.db`.  Use `.trace` to keep your history.

## Objectives


### Simple adding and deleting


1. The Texas vote is close!  Add 2 new voters, and fabricate a vote for each of the 2 incumbent senators of Texas.  Make up their names and info.

2. Insert another politician, "Donald Trump".  Add suitable attributes and delete one of the senators from New Jersey.  Add Trump there instead.  Give Trump all the votes from the deleted politician.

**Extra Credit: SQL Shortcuts and Intricacies** - Chances are you wrote out a pretty long SQL statement to do your `INSERT` statement.  How could you shorten it?  Careful!  SQLite, just like PostgreSQL and MySQL, have subtle and annoying differences to the standard SQL language.  Make sure you use SQLite syntax for this!


### Delete specific voters

1. Find all the voters that are not registered as republican or democrat (AND only voted once), and delete them.

2. Delete all the voters (and their votes) that are homeowners, employed, have no children, and have been with their party for less than 3 years AND have voted for politicians that speak at a grade level higher than 12.


### Updating records for more fudging

1. Update the votes for all the men over 80 that have no children.  Change their vote to be for the secret politician with ID 346.

2. Update the votes for top smarty pants politician (based on their speaking level - grade_1996).  Shift the votes instead to the congress person that speaks at the lowest grade level.

Paste the text from your `trace` file into the gist and star it for future reference on `JOIN`'s and other SQL calls.  Include the schemas of the 3 tables in the gist.  Include some on the output of the queries if you're worried you won't remember all this syntax! 

##Releases
###Release 0 

##Optimize Your Learning 

##Resources