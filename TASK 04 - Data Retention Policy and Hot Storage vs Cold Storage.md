**STEP 1:** Decide the Retention Policy



Keep last 2 years of parking sensor data in Hot Storage



Move data older than 2 years to Cold Storage (Archive)



Delete archived data from hot tables to control growth



**Reason:** 50M rows/month → ~1.2B rows in 2 years → needs lifecycle control



------------------------------------------------------------------------



**STEP 8:** Explain the difference between "Hot Storage" and "Cold Storage"



**Hot Storage**



Delta tables



Frequently queried



Supports updates \& deletes



Used for dashboards \& analytics



**Cold Storage**



Parquet files



Cheap \& long-term



Rarely accessed



Used for audits \& compliance

