# ubuntu-linux-troubleshooting

```bash
System Security Services Daemon failure
```
## Ubuntu fails to start System Security Services Daemon
Ubuntu takes a lot of time in booting and checking the logs, I see a lot of error related to this daemon. There are several fixes, but here I will disable it.

To see the error you can type
```
systemctl status sssd
```
To stop it

```bash
sudo systemctl stop sssd
sudo systemctl disable sssd
```

To enable you can follow this link
[ubuntu sssd issue](https://askubuntu.com/questions/1288626/ubuntu-20-10-sssd-system-security-services-daemon-failure)

