# MongoDB

## Running In Docker
https://hub.docker.com/_/mongo

```shell
docker run --name wrangle-mongo -p 27017:27017 -d mongo:3.6.18
```

## Connecting to shell
```shell
docker exec -it wrangle-mongo bash
```

## Port Forwarding
```shell 
ssh -p 12923 -N -L 127.0.0.1:27017:driverless-ai:27017 root@197.95.152.171
```

## Web References
- https://docs.bitnami.com/vmware/faq/get-started/access-ssh-tunnel/
- https://www.ssh.com/ssh/tunneling/example