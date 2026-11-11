select email,full_name
from users 
where role='admin'

select name,price
from products
where category='Electronics' and price<50
order by price ASC

select email,created_at
from users 
order by created_at desc
limit 10;

select name,category,price
from products
where name like '%Keyboard%'
order by name asc

select email,full_name
from users
where full_name like 'A%'

select name,price
from products
where category='Furniture'
order by price asc
limit 5;

select name,category,price
from products
 where price between 100 and 200
order by price desc
limit 10;

select name,price
from products
order by price desc 
limit 5
offset 5

orders будет обращаться к users id так как id представляет собой уникальное множество чисел,тем самым можно избежать далнейшей путаницы
