# ip_location

### GeoIP tool
> The ip_location.py basically has 2x ways to run:

```
$ ip_location.py
NOTE:
1. single ip as argv:
        ip_location.py 8.8.8.8
2. stdin a list of IPs with -s parm:
        cat list| ip_location.py -s
```


**Limitation**
When querying in batch with -s,
The system will automatically ban any IP addresses doing over 150 requests per minute. To unban your IP go to [ip-api](http://outgoing.ip-api.com/docs/api:batch).