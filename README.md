# left_join
we are going to learn left _join

create database test4
create table ram (full_name varchar(30))
insert into ram values(
"kumar"),
("kumar"),
("kumar"),
("kumar"),
("kumar")

create table syam (full_name varchar(30))
insert into syam values(
"kumar"),
("kumar"),
("kumar")

select * from ram r
left join syam s
on r.full_name=s.full_name;

/*output

15 times kumar */

select count(*) from ram r
left join syam s
on r.full_name=s.full_name;

/*output

15

*/
