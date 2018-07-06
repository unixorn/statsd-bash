# statsd-bash

Bash script to write to statsd

Usage: `write-statsd metricName metricValue`

`write-statsd` defaults to using port 8125 on localhost; set `STATSD_HOST` and `STATSD_PORT` in the environment to change that.
