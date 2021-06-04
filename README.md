# syslog

Test syslog configuration

## Using Netcat
```bash
echo "message" | nc -q0 127.0.0.1 514
```

## Using Logger
```bash
logger "test message
```
