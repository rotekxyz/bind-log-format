# bind-log-format
client log format back to less than bind-9.9.X

## Description
More than "bind-9.10.X" log format on client section.

```
23-May-2018 04:02:16.710 queries: info: client @0x7f30d8000a30 127.0.0.1#41446 (www.example.com): query: www.example.com IN A + (127.0.0.1)

```

This patch is following format.
without client hex-address.(old format)

```
23-May-2018 04:02:16.710 queries: info: client 127.0.0.1#59305 (www.example.com): query: www.example.com IN A + (127.0.0.1)
```
 
This patch for emergency use.

