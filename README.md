# Deployment

## MySQL

## MySQL with Docker CLI

* Image
  * (...)
* Port
  * (...)
* Volume
  * (...)

```bash
#mkdir data
docker run --detach --name some-mariadb --env MARIADB_ALLOW_EMPTY_ROOT_PASSWORD=1 -p 3306:3306 -v ./data:/var/lib/mysql mariadb:latest
```

```bash
#TODO: Remove Mariadb Container
```

### MariaDB with Compose

```yaml
#...
```

## References
### https://hub.docker.com/_/mariadb