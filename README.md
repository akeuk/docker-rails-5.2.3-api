## Development

### Rails server (with MySQL service)

```sh
docker-compose up app
```

When Dockerfile-dev has changed.

```sh
docker-compose up --build app
```

### Bash

```sh
docker-compose exec app bash
```

Without app container.

```sh
docker-compose run --rm app bash
```

### Stop all services

```sh
docker-compose down
```

