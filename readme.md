# Editor API

## Requirements

- Install docker repo for project and up needed containers

## Install

- `docker-compose build nginx mysql php-worker`

## Development

- Up docker's containers:

`docker-compose up -d nginx mysql php-worker`
- Do all operations from `workspace` container
-  Enter to the `workspace` docker's container:
```
docker exec -it editor_workspace_1 bash
```