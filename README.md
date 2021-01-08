# Pathidea_Data

### Description
Pathidea_Data is a collection of bugs collected through ten open-source projects.

### Summary

|Project|# studied bugs|total # bugs collected|
|---|---|---|
|ActiveMQ|594|4,649|
|Hadoop Commons|725|7,259| 
|HDFS|1,116|5,668|
|MAPREDUCE|575|4,154|
|YARN|576|3,778|
|Hive|2,231|11,862|
|Storm|380|1,507|
|ZooKeeper|288|1,827|
|Total|6,535|40,704|

### Project structure

```
Pathidea_Data
│
├── bug_reports:				List of bug reports
│   ├── ActiveMQ	
│   ├── ├── AMQ-100.json			Bug report basic content
│   │   ├── comments				Comments for each associated bug report
│   │   └── details				Details for each associated bug report
│   ├── ...
├── vsm						VSMScore after normalization
├── code_changes				Detailed Java file changes for each bug report 
├── vsm_segmentation				Per-file score at different segmentation size
├── log				List of logged classes extracted from bug reports
└── path				List of classes that are found on the execution paths
```
