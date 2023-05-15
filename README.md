# linux service sample

```
[Unit]
Description=My test service
After=multi-user.target[Service]
Type=simple
Restart=always
ExecStart=/path/to/python /path/to/file.py
[Install]
WantedBy=multi-user.target
```
