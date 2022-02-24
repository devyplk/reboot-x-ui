# reboot-x-ui
```
wget https://raw.githubusercontent.com/devyplk/reboot-x-ui/main/reboot-x-ui; chmod 777 reboot-x-ui; ./reboot-x-ui
```
# Add Cronjob for every sunday 00:00
```
(crontab -l && echo "0 0 * * 0 ./reboot-x-ui")
```
