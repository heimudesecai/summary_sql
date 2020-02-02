# summary_sql
LAG (scalar_expression [,offset] [,default])  
    OVER ( [ partition_by_clause ] order_by_clause )  
select the value before "offset" rows
scalar_expression: the column returned

LEAD (scalar_expression [,offset] [,default])  
    OVER ( [ partition_by_clause ] order_by_clause )  
select the value after "offset" rows
scalar_expression: the column returned

set the format of the data and the column name
select to_char(t1.visit_date, 'yyyy-mm-dd') "visit_date"
