# Linux

generate csr for webserver 
```shell
openssl req -new -newkey rsa:2048 -nodes -keyout server.key -out server.csr
```

lauch tcpdump for specific port and interface
```shell
tcpdump -i eno0 port 67
````
