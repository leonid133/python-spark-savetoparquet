#### Read from noaa .gz Weather station data and save to parquet

```
$SPARK_HOME/bin/spark-submit \                                                   
--master "local[*]" \
$SAVETOPARQUETPATH/save_to_parquet.py\
$SOURCE\
$OUTPUT
```
