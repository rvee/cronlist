# cronlist
Displays system wide cronjob list

Usage:
./cron-list.sh
mi    h   d  m  w    user       command
0     0   *  *  1    harry       <Command>
0     0   *  *  *    rvee       cron command
0     0   *  *  *    admin       ps -A
01    *   *  *  *    rocks       run-parts /etc/cron.hourly
*/10  *   *  *  *    nobody     sudo rm -rf /tmp/*
