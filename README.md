# DesignDocuments

## Functional Reqs: 
Building event streaming platform for apps like spotify and amazon prime to track user events and aggregate the TopN songs played world wide in Realtime with freshness less than 30 mins.

## Non-Funtional Reqs: 
Highly Available
Accurate
Scalable
Fault-Tolerant
 
## Scale
```
Total Users - 550 Million
Max Active Users At Once - 100 Million
Events/Secs - 100 Million
Volume/Sec - 25 Gb/sec
```
This can be achieved in both batch and streaming modes.
