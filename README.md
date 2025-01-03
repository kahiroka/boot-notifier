# Boot Notifier
Boot notification with hostname and IP address using LINE Messaging API/Discord Webhook

# Files
Linux: Systemd  
[line/boot-notifier.service](line/boot-notifier.service)  
[discord/boot-notifier.service](discord/boot-notifier.service)

Windows: Task Scheduler  
[line/BootNotifier.xml](line/BootNotifier.xml)  
[discord/BootNotifier.xml](discord/BootNotifier.xml)

# Usage
First replace BEARER_TOKEN, USER_ID, WEBHOOK_ID and WEBHOOK_TOKEN in the file.

Linux  
```
$ sudo systemctl enable boot-norifier
$ sudo systemctl start boot-notifier # for testing
```

Windows  
Copy & paste command and arguments in the file or just import the file.
