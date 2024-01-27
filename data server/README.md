# Data Server

This server is intended for databases and their management.

- **budibase**: https://hub.docker.com/r/budibase/budibase
- **mysql**: https://hub.docker.com/_/mysql

## Launch

Docker Compose is used to launch containers. If there is a `.env.example` file in the project folder, it should be renamed to `.env` and your variables should be specified in it.

```shell
# Launch
docker compose up -d
```