### 1. `scripts/run_rclonesync.sh`

I set the `scripts/run_rclonesync.sh` script to run as a cronjob every fourth hour starting at 00:00:

`0 0,4,8,12,16,20 * * * /home/pi/devel/rpi-books/scripts/run_rclonesync.sh >> /home/pi/devel/rpi-books/logs/run_rclonesync.out 2>&1`

### 2. `scripts/update_news.sh`

I set the `scripts/update_news.sh` script to run as a cronjob every fourth hour starting at 02:00:

`0 2,6,10,14,18,22 * * * /home/pi/devel/rpi-books/scripts/update_news.sh >> /home/pi/devel/rpi-books/logs/update_news.out 2>&1`
