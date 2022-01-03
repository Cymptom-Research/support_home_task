# support_home_task

This home task is ment to test your ability to learn and oprate:
* docker
* neo4j DB


## Assignment

* Install docker
* Run neo4j localy in a docker container
* Load [this DB dump](movies.dump) into the container DB.
  * Use `neo4j-admin load`
  * You may need to run this inside the container
  * You may need to run the container without the DB running to load the dump (running it with `-it --entrypoint=sh` might help).
* Log into the Web UI of the DB

### Run cypher query to answer these questions:


1. When was `V for Vendetta` released?
2. Who acted in any `Spider-Man` movie that appear in the DB? When were they born? (notice that Spider-Man is a partial name of a movie)
3. What movies were release after `2010`?
4. In which movies `Keanu Reeves` `ACTED_IN`?
5. Who are the directors in the DB? (notice `DIRECTED` relationship)

### Opotional Questions for extra points ^^ 

7. Who were the actors which acted in a movie that `James Thompson` `REVIEWED`?
8. Find co-actors who have nоt worked with `Keanu Reeves`.
9. Return for each actor, Which movies did he acted in and the total sum of movies.

Please submmit your responces using mail.
 
