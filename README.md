# Homebridge - LaMetric Time

make notificationswitches for LaMetric Time


Example config.json:
```
    "accessories": [
        {
            "name": "Hello",
            "host": "192.168.2.100",
            "apikey": "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX",
            "notify_text": "hello from homekit",
            "notify_icon": "3061",
            "notify_sound": "dog",
            "notify_cycles": 3,
            "accessory": "LaMetricTime"
        }
    ]
```