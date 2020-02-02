# summary_sql
LAG (scalar_expression [,offset] [,default])  
    OVER ( [ partition_by_clause ] order_by_clause )  
select the value before "offset" rows
scalar_expression: the column returned

LEAD (scalar_expression [,offset] [,default])  
    OVER ( [ partition_by_clause ] order_by_clause )  
select the value after "offset" rows
scalar_expression: the column returned
