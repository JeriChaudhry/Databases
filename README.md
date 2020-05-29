# Databases


Sakila database test. JERI CHAUDHRY!

1 - SELECT * FROM actor;

2 - SELECT first_name FROM actor WHERE first_name='John';

3 - SELECT last_name FROM actor WHERE last_name='Neeson';

4 - SELECT * FROM actor where actor_id%10=0;

5 - SELECT description FROM film WHERE film_id=100;
(A Beautiful Drama of a Dentist
And a Composer who must
Battle a Sumo Wrestler in
The First Manned Space Station)

6 - SELECT title FROM film where rating='R';

7 - SELECT title FROM film WHERE NOT rating ='R';

8 - SELECT title FROM film order by length limit 10; 
   (there are some films of length 47 which are being missed out)

9 - SELECT title FROM film order by length limit 10;

10 - SELECT title FROM film where special_features like '%Deleted Scenes%';

11 - SELECT last_name FROM actor group by last_name having count(*)<2;

12 - SELECT last_name FROM actor group by last_name having count(*)>1;

13 - SELECT actor_id FROM film_actor GROUP BY actor_id ORDER BY COUNT(*) DESC LIMIT 1;

14 - SELECT film_id FROM film WHERE title='Academy Dinosaur';

15 - 
