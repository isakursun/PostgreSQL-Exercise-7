1. SELECT rating, COUNT(*) FROM film
   GROUP BY rating;

   ![](./images/1.png)

2. SELECT replacement_cost, COUNT(*) FROM film
   GROUP BY replacement_cost
   HAVING COUNT(*) > 50;

   ![](./images/2.png)

3. SELECT store_id, COUNT(*) FROM customer
   GROUP BY store_id;

   ![](./images/3.png)

4. SELECT country_id, COUNT(*) FROM city
   GROUP BY country_id
   ORDER BY COUNT(*) DESC
   LIMIT 1;

   ![](./images/4.png)