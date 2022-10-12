# Python-Notification-Desktop-Notification-with-Python
Python Notification, Desktop Notification with Python

### There is a story behind this project:
**In my professional life, I work around 8 to 10 hours every day. It is excruciating for a person to set a chair for around 8 hours. That is why my Doctor wife suggests me, I need a break after every 1 or 1.5 hours. Furthermore, maintain this break period every 1 or 1.5 hours, it is impossible for me to create an alarm on my laptop or phone for this break period. That is why I have made Python code and run it. It notifies me after 1 hour for a break.**

#### Install 
```
pip install plyer
```

##### Run this code
```
import time
from plyer import notification

if __name__=="__main__":
    while True:
        notification.notify(
            title = "ALERT!!",
            message = "Take a Break Nowshad! It has been an hour!",
            timeout = 10
        )
        time.sleep(3600)
```

 ![Break-After-1Hour](https://github.com/NowshadRuhan/Desktop-Notification-with-Python/blob/main/py_notification.png?raw=true) 
