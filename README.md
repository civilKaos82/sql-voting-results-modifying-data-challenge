# SQL Queries: Insert, Update, and Delete 
 
## Summary 
In our work with the  SQL Tutor and previous challenges, we've had some practice reading data from a database.  In other words, we've written a lot of select statements.  Now we're going to get some practice modifying the data in a database:  creating, updating, and deleting records.


## Releases
### Pre-release:  Review the Schema
We'll be working with the `voting_results.db` SQLite database.  Take a look at the database's schema, so we know which tables exist in the database, which fields are on those tables, and how the tables relate to each other.


###Release 0 : Simple adding and deleting

1. The Texas vote is close!  Add 2 new voters, and fabricate a vote for each of the 2 current senators of Texas.  Make up their names and info.

2. Insert another politician, "Ada Lovelace".  Add suitable attributes and delete one of the senators from New Jersey.  Add Lovelace there instead.  Give Lovelace all the votes from the deleted politician.

**Extra Credit: SQL Shortcuts and Intricacies** - Chances are you wrote out a pretty long SQL statement to do your `INSERT` statement.  How could you shorten it?  Careful!  SQLite, just like PostgreSQL and MySQL, has subtle and annoying differences to the standard SQL language.  Make sure you use SQLite syntax for this!


###Release 1 : Delete specific voters

1. Find all the voters that are not registered as republican or democrat (AND only voted once), and delete them.

2. Delete all the voters (and their votes) that are homeowners, employed, have no children, and have been with their party for less than 3 years AND have voted for politicians that speak at a grade level higher than 12.


###Release 2 : Updating records for more fudging

1. Update the votes for all the men over 80 that have no children.  Change their vote to be for the secret politician with ID 346.

2. Update the votes for top smarty pants politician (based on their speaking level - grade_1996).  Shift the votes instead to the congress person that speaks at the lowest grade level.

Paste the text from your `trace` file into the source file along with the schemas of the 3 tables. If you want to use this as a future reference, you might also include some on the output of the queries to help remember all this syntax!


##Optimize Your Learning 

##Resources
