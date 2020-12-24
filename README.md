# program-6
create table store(order_no int(5), code  varchar(10), item varchar(20), quantity int(2), price int(5), discount int(2), MRP int(5),primary key(order_no));

insert into store values(90001,'AX5432','SSHH',2,649,30,879);

insert into store values(90002,'BY3471','TTAA',1,559,25,720);

insert into store values(90003,'CZ6312','WWCC',2,432,50,832);

insert into store values(90004,'DL7481','HHEE',4,1345,60,1675);

insert into store values(90005,'EQ4954','MMAA',3,800,30,1255);

select * from store;

create view itm_qty as select item,quantity from store;

select * from itm_qty;

drop view itm_qty;
