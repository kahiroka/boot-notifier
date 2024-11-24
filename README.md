# Boot Notifier
Boot notification with hostname and IP address using LINE Messaging API

# Files
Linux: Systemd  
[boot-notifier.service](boot-notifier.service)

Windows: Task Scheduler  
[BootNotifier.xml](BootNotifier.xml)

# Usage
First replace bearer token and UserID in the file.

Linux  
```
$ sudo systemctl enable boot-norifier
$ sudo systemctl start boot-notifier # for testing
```

Windows  
Copy & paste command and arguments in the file or just import the file.