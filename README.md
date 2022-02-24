# reboot-x-ui
```
wget https://raw.githubusercontent.com/devyplk/reboot-x-ui/main/reboot; chmod 777 reboot; ./reboot
```
# Add Cronjob for every sunday 00:00
```
(crontab -l && echo "0 0 * * 0 ./reboot")
```
