# memo
update customer set gender='W' where name = '김문영'
select name, gender from customer where name ='김문영';
update customer set mileage=0 where name = '이상훈';
select name, mileage from customer where name = '이상훈';
update customer set mileage=10000 where gender='W' and age>=30 and age<=39;
select name, gender, age, mileage from customer where gender='W' and age>=30 and age<=39;
delete from customer where name = '유지수';
select * from customer where name = '유지수';
select num, name, address, from customer where address like '%성남시 중원구 광명로 123%';
delete from customer where num = 8;
select * from customer where num = 8;
delete from customer;
