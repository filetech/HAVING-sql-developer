-- HAVING ONLY WITH AGGREGATIONS 
-- SUSCRIBE 
select sum(columname), 
columname2 
from tablename
group by columname2
having sum(columname) > 0;
