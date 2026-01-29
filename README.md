# Homework 2

Queries made:

```

SELECT COUNT(*) AS row_count
FROM `terraform-demo-484500.zoomcamp.yellow_tripdata_2021_03`


SELECT COUNT(*) AS row_count
FROM `terraform-demo-484500.zoomcamp.green_tripdata`
WHERE lpep_pickup_datetime >= TIMESTAMP('2020-01-01')
  AND lpep_pickup_datetime <  TIMESTAMP('2021-01-01');


SELECT COUNT(*) AS row_count
FROM `terraform-demo-484500.zoomcamp.yellow_tripdata`
WHERE tpep_pickup_datetime >= TIMESTAMP('2020-01-01')
  AND tpep_pickup_datetime <  TIMESTAMP('2021-01-01');


```
