nc-rtt
======

netcat based RTT reader for JLinkGDBServer as an alternative to JLinkRTTClient which
doesn't re-connect to the log output automatically. Useful for Nordic Semiconductor or
other kind of embedded command line debugging.

Copyright (C) 2017 Peter Honeder
MIT License

## Usage

The script starts listening on JLinkGDBServer port 19021, and prints "debugging ended" every
time it re-connects.

```
./nc-rtt
```

