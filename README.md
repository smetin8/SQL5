# SQL5
Homework-5-in-kodluyoruz



select title from film
where title like '%n'
order by length asc
limit 5;


select title from film
where title like '%n'
order by length desc
limit 5;

select title from film
where title like '%n' 
order by length desc
limit 5;



select last_name from customer
where store_id = 1
order by store_id desc
limit 5;
