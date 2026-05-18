
This is the production directory!

* * * * * /home/jtf/projects/neighbor-display/power-relations.github.io/run_pge.sh

Crontab runs run_pge.sh every minute

This runs PGE_to_display.py (which uses outage_lib.py) with logging and error to runlog.txt

This fetches new data from PGE -- if it's new, it generates a new display file latest_outages.json and archives both the raw PGE data and the display json in /archive

