# watchlogtails
Watches /var/log and monitors the output of backup.sh and enable_avscan related log files. Also has a script to launch backup and avscan jobs for initial testing.

NOTE: This script is pointless without:

  https://github.com/hp6000x/backup.sh
  
  https://github.com/hp6000x/docsbackup
  
and

  https://github.com/hp6000x/enable_avscan
  
Get them, read them, configure them, run them, then come back here.

This repo contains three scripts:

viewlogtails  : Shows the tails of avscan and backup.sh logs

watchlogtails : Uses watch to monitor the output of viewlogtails

allthethings  : Launches backup.sh and daily, weekly and monthly av scans, if installed.


Put all three scripts in the same folder ($HOME/bin is a good place. I keep all my scripts in /pub/scripts, just make sure it's in your PATH)

As with all my scripts, I'd recommend reading these and thoroughly understanding what they do before running them. These three are pretty short and straightforward.
