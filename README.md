# Syslog Configuration

| Facility	| Description |
|:---------|:-----------|
| auth/authpriv |	security/authorization messages |
| cron |	crond and atd daemons messages |
| daemon |	other system daemons |
| kern | kernel messages |
| local0 – local7 | reserved for local use |
| lpr |	line printer subsystem |
| mail | mail subsystem |
| news | USENET news subsystem |
| syslog | messages generated internally by the system log daemon |
| user | generic user-level messages |
| uucp | UUCP subsystem |

## Test syslog configuration

### Using Netcat
```bash
echo "message" | nc -q0 127.0.0.1 514
```

### Using Logger
```bash
logger "test message"
```
