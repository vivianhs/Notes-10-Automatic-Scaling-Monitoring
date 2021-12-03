# Notes-10-Automatic-Scaling-Monitoring
CIT 114 Notes 10


Notes 10: Automatic Scaling & Monitoring


### Monitoring with CloudWatch:
With cloudwatch monitoring, users can get alerts when things go wrong
View metrics for where resources are being allocated
Create dashboards
Create events based on monitoring
Set alarms based on usage, or money spent (ex. Alarm activity)

### Elastic Load Balancing
Load Balancing >> Spreads out network traffic among multiple servers
Provides redundancy (if one server goes down, no break in services)

### Auto Scaling
Allows to launch or terminate instances controlled by CouldWatch alarms. The metrics include auto-scale group metrics such as the minimum and maximum group size and the in-service, pending, standby and total instances.
