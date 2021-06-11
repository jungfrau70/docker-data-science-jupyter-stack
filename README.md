# data-science-jupyter-stack

## How to run
```
# 1 - build the images
# !This might take some minutes, since some low level packages have to be installed
docker-compose up -build

# 2 - launch the stack

docker-compose up -d

# 3 - stop the stack

docker-compose down
```

## Service - Port Mappings
| Service | Port |
| ------- | ---- |
| Jupyter | 8888 |
| Minio   | 9000 |
| Portainer | 9090 |
| Postgres | 5432 |
| Mysql   | 3306 |
| adminer  | 8080 |
