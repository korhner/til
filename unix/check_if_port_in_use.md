# Check If A Port Is In Use

The ```lsof``` command is used to list open files. This includes listing network connections.
```lsof -i TCP:8000```

Output:
```
COMMAND   PID USER   FD   TYPE    DEVICE SIZE/OFF NODE NAME
java    24508 root  117u  IPv6 268149838      0t0  TCP *:irdmi (LISTEN)
```
