to run top.sh command every 2 second , just add a crontab like this:

* * * * * sleep 3 && /bin/bash /opt/monitoring/prometheus/top
