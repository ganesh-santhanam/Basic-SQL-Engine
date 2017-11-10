# Basic-SQL-Engine
1.Uses SQL Parser -https://github.com/andialbrecht/sqlparse . To install run - pip install sqlparse
2. Run python main.py
3. Input your query at the prompt.
4. Type "QUIT" or "quit" to quit.

Queries implemented 

1. Select:

select * from table1;
2. Aggregate functions: sum, average, max and min

select max(col1) from table1;

3. Distinct Clause

select distinct(col1) from table_name;

4 Where clause 

select col1,col2 from table1,table2 where col1 = 10 AND col2 = 20;

5 Join 

a. select * from table1, table2 where table1.col1=table2.col2; b. select col1,col2 from table1,table2 where table1.col1=table2.col2;
