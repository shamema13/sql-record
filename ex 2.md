## DCL COMMANDS

```
-- insert a new column profit in productmaster

alter table productmaster add(profit number(20));
```
```
-- find the profit value as, profit as profit=sp-cp in productmaster

update productmaster set profit=sp-cp;

```
```
-- display the record of productmaster where sp is between 8&9

select sp from productmaster where sp between 8 and 9;
```