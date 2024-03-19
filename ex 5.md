## create table
```

create table salesmaster1(
    sno varchar2(10),
    sname varchar2(20),
    address varchar2(20),
    city varchar2(10),
    state varchar2(12),
    pincode number(6),
    salaryamt number(6),
    target number(6),
    year number(10),
    remarks varchar2(20)
);
```

## alter table to create sno as primary key
```
alter table salesmaster1 modify(
    sno varchar2(10) primary key
 );
```

## create a constraint named `sal_no` to check if the sno starts with letter s
```
alter table salesmaster1 modify(
    sno varchar2(10) constraint sal_no1 check(sno like '%s')
);
```
