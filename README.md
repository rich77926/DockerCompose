# DockerCompose

## File name sould be docker-compose.yaml
```
version: '3'
services:
  redis:
    container_name: redis
    image: redis
    ports:
      - "6379:6379"
    volumn:
      - source:target
    env_file:
    environment:
```