# WordPress Docker SSL

## Configuration environment

create a file `.env` or copy the file `.env.example` to `.env` and set the values

```bash
DOMAIN_NAME=example.com,www.example.com
LETSENCRYPT_EMAIL=webmaster@example.com
```

## Start containers

```bash
docker-compose up -d
```