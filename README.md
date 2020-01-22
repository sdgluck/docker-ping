# docker-ping

based on https://hub.docker.com/r/willfarrell/ping

## CMD
- `HOSTNAME` Server you would like to continuously ping [ default=localhost ]

To override the hostname override the CMD, e.g.:

```shell script
docker run sdgluck/ping -c 'sh ping google.com'
```

## ENV
- `TIMEOUT` Number of seconds between timeouts [ default=300 ]

Example:

```shell script
docker run sdgluck/ping --env TIMEOUT=1
```
