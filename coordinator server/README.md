# Coordinator Server

The server is designed for managing clusters/containers.

- **Rancher**: https://hub.docker.com/r/rancher/rancher

## Launch

Docker Compose is used to launch containers. If there is a `.env.example` file in the project folder, it should be renamed to `.env` and your variables should be specified in it.

```shell
# Launch
docker compose up -d
```