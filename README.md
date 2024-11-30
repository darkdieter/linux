# Linux

generate csr for webserver 
```shell
openssl req -new -newkey rsa:4096 -nodes -keyout server.key -out server.csr
```
convert p7b to pem format
```shell
openssl pkcs7 -print_certs -in server.p7b -out server.pem
```


lauch tcpdump for specific port and interface
```shell
tcpdump -i eno0 port 67
````
