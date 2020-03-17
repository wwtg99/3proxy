3APA3A 3proxy tiny proxy server
===============================

# Deployment

Http Proxy on port 8080 and socks proxy on port 1080.

## Deploy 3proxy
```
docker run --name 3proxy -p 8080:8080 -p 1080:1080 -d wwtg99/3proxy
```

## Deploy 3proxy and apply your own configuration
```
docker run --name 3proxy -p 8080:8080 -p 1080:1080 -v /opt/3proxy.cfg:/etc/3proxy.cfg -d wwtg99/3proxy
```
