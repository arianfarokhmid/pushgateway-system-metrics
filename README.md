crontab doesnt support less than 1 min, so in script i added sleep 3 sec and cron tab runs it every 3 sec
to run top.sh command every 3 second , just add a crontab like this:

* * * * * /bin/bash top.sh
