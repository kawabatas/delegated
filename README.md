# delegated

[DeleGate](http://ja.delegate.org/delegate/) is a multipurpose proxy server which relays various application protocols on TCP/IP or UDP/IP

## Build
```
docker build -t kawabatas/delegated .
```

## Run
```
docker run -p 1080:1080 kawabatas/delegated
```

## Check
```
curl -x socks5h://localhost:1080 ifconfig.ovh
```
