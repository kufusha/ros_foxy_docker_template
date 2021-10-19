
## dependencies
- docker
- docker-compose

``` diff
- Linux は xhost local:
- Winは VcXsrvで環境構築している前提
```

## usage

1. `cd Docker/(Linux OR Win)` 
2. `docker-compose up -d --build`
3. `docker-compose exec sample bash`
