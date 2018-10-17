# Marcus Brock
## CT-406-HW4-Razor
###The fourth homework assignment for CT-406

This assignment focused on creating an ASP.NET CORE website that locally hosted a movie database. The main point of the assignment was to 
do this with the **Razor views** rather than the usual MVC setup.
This website contains seeded database entries for movies that can be edited, deleted, and searched for.

Razor allow for the transition from cs(c#) to cshtml or another specified markup as needed. This means that anyone who is more familiar 
with a different markup style can use Razor views to create webpages. 

*At the moment, the solution has one error, which is with the file/schedule uploading portion of th eassignment. This is due to a 
database error that is keeping the schedule portion of the webpage from properly loading.*

*The issue given is that the original table for the database that holds all of the movie data is unable to allow the schedule tabble to
be created due to a conflict with the 'ratings' variable for the movie table not being able to accept NULL values*

*I have tried to manually update the movie database to allow the 'ratings' variable to accept NULL values, but that only caused more 
errors*

*Currently, all other parts of the assignment are working as intended*
