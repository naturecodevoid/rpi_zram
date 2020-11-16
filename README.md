# rpi_zram
Script to dynamically enable ZRAM on a Raspberry Pi or other Linux system.

Automatically detects the number of CPU cores to allocate to ZRAM computation, disables existing swap and enables ZRAM swap.

Download the script

`curl -o $HOME/zram.sh https://raw.githubusercontent.com/naturecodevoid/rpi_zram/master/zram.sh`

run `sudo crontab -e` and add `@reboot /bin/bash /home/ubuntu/zram.sh`
