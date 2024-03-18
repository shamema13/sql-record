## DDL COMMANDS
CREATING TABLE 1
```
create table clientmaster1( 
cno number(2),
name char(10),
add1 varchar(30),
city varchar(20),
state varchar(30),
pincode number(10),
balancedue number(30)
);
```
INSERTING VALUES
```
insert into clientmaster1 values('1','shami1','ppy1','er','Tamilnadu','890567','900');
insert into clientmaster1 values('2','shami2','ppy2','cbe','Tamilnadu','890367','100');
insert into clientmaster1 values('3','shami3','ppy2','cbe','Tamilnadu','898567','700');
insert into clientmaster1 values('4','shami4','ppy3','er','Tamilnadu','890967','970');
insert into clientmaster1 values('5','shami5','ppy2','cbe','Tamilnadu','894567','700');
insert into clientmaster1 values('6','shami6','ppy4','amdra','andra','890507','990');
insert into clientmaster1 values('7','shami7','ppy1','er','Tamilnadu','890367','980');

```
CREATING TABLE 2
```
create table productmaster(
    pno number(7),
    description varchar(20),
    unit number(15),
    quantity number(20),
    sp number(10),
    cp number(10)
);
```
INSERTING VALUES
```
insert  into productmaster values('1','pendrive','2','3','8','9');
insert  into productmaster values('2','mouse','3','2','6','9');
insert  into productmaster values('3','keyboard','1','6','10','8');
insert  into productmaster values('4','laptop','4','8','9','7');
insert  into productmaster values('5','mobile','3','6','9','7');
insert  into productmaster values('6','adapter','2','1','7','6');
insert  into productmaster values('7','wire','4','6','9','8');
```


DESCRIBE 

```
describe productmaster;

```
