## Aggregation query  

COUNT(*)
SUM(*)
AVG(*)
MAX(*)
MIN(*)

GROUP BY


## Multi-table query
FROM ... , ...  
> above this,there is ... x ... , it's multiplication.

```sql
SELECT
    s.id sid,
    s.name,
    s.gender,
    s.score,
    c.id cid,
    c.name cname
FROM students s, classes c
WHERE s.gender = 'M' AND c.id = 1;
-- this correct
```

## Join query
_INNER JOIN ... ON ..._

LEFT OUTER JOIN

RIGHT OUTER JOIN 

FULL OUTER JOIN

