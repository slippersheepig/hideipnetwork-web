#### For Railway deploy, please visit
##### https://github.com/slippersheepig/hideipnetwork-web-railway
`docker-compose.yml`
```bash
services:
  hnet:
    image: sheepgreen/hnet
    container_name: hnet
    ports:
      - 56559:56559
    restart: always
```
