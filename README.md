# lindas-joshuas


```sql
SELECT
  year,
  SUM(number) as Joshuas
FROM
  `bigquery-public-data.usa_names.usa_1910_current`
WHERE
  name='Joshua'
GROUP BY
  year
ORDER BY
  year;
  ```
