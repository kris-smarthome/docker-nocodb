# NOCODB
Services:

- nocodb: no-code database platform
- postgres: relational database

## usage
Clone this repository to your local machine, edit the config file to match your environment, and run docker compose.

```bash
git clone https://github.com/kris-smarthome/docker-nocodb.git
cd docker-nocodb
nano .env
docker compose up -d
```

> [!NOTE]
> This stack assumes the use of N8N which incldes Traefik, remove labels and networks if Traefik is not used. 