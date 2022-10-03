# nginx-reverse-proxy

## How to start server

```sh
# Init & Update git submodule
git submodule init

git submodule update

# Chnage to stubby-api directory
cd stubby-api

# Start stubby-api
docker compose up -d

# Back to nginx directory
cd ..

docker compose up -d

# Check docker process
docker ps
```