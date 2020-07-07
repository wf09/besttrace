下载链接：

```shell
wget https://github.com/wf09/besttrace/raw/master/besttrace4linux/besttrace chmod+x besttrace
```

```shell
wget https://github.fly97.workers.dev/wf09/besttrace/raw/master/besttrace4linux/besttrace 
chmod+x besttrace
```

```shell
wget https://cdn.jsdelivr.net/gh/wf09/besttrace/besttrace4linux/besttrace
chmod+x besttrace
```

用法

```
root@VM-8-9-ubuntu:~# ./besttrace 
Usage of ./besttrace host [ packetlen ]
  -6, --ipv6
        Use ipv6.
  -J, --json
        Print traceroute result with JSON format.
  -g, --lang string
        Language only supported cn and en now.
  -m, --maxhop int
        Specifies the maximum number of hops (max time-to-live value) traceroute will probe. The default is 30. (default 30)
  -a, --noas
        Do not try to map IP addresses to AS when displaying them.
  -n, --nodomain
        Do not try to map IP addresses to host names when displaying them.
  -l, --nolocation
        Do not try to map IP addresses to location when displaying them.
  -q, --queries int
        Sets the number of probe packets per hop. The default is 3. (default 3)
  -z, --sendtime int
        Minimal time interval between probes (default 0). 
        If the value is more than 10, then it specifies a number in milliseconds, else it is a number of seconds (float point values allowed too). 
        Useful when some routers use rate-limit for ICMP messages.
  -f, --starthop int
        Specifies with what TTL to start. Defaults to 1. (default 1)
  --sync
        Send icmp package by sync.
  -T, --tcp
        Use TCP SYN for probes.
  -V, --version
        Print the version and exit.
  -w, --waittime int
        Set the time (in seconds) to wait for a response to a probe. (default 3)

root@VM-8-9-ubuntu:~# 
```

