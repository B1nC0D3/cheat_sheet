# linux service sample

sudo nano /etc/systemd/system/name_of.service

```
[Unit]
Description=Ur description of service
After=multi-user.target[Service]
Type=simple
Restart=always
ExecStart=/path/to/python /path/to/file.py
[Install]
WantedBy=multi-user.target
```
