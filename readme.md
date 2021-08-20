**Test**  

Codeblock 1
```
adding terminal code
```

Codeblock 2
```python
import pandas as pd
df = pd.Series([1,2,3],index=['a','b','c'])
```

```r
df <- read.csv("https://...")
model <- lm(df)
```
  
Codeblock3
```SQL
SELECT t.* FROM stadium t
 LEFT JOIN stadium p1 ON t.id — 1 = p1.id
 LEFT JOIN stadium p2 ON t.id — 2 = p2.id
 LEFT JOIN stadium n1 ON t.id + 1 = n1.id
 LEFT JOIN stadium n2 ON t.id + 2 = n2.id
 WHERE (t.people >= 100 AND p1.people >= 100 AND p2.people >= 100)
 OR (t.people >= 100 AND n1.people >= 100 AND n2.people >= 100)
 OR (t.people >= 100 AND n1.people >= 100 AND p1.people >= 100)
 ORDER BY id;
```
