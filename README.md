# bpi-build

This is a docker system environment which is run Ubuntu 15.10 for Banana PI source code compile.

Find container id:
```bash
docker ps -a
```

Run container:
```bash
docker start <id>
```

Use container:
```bash
docker inspect <id>
ssh root@<IP>
```
