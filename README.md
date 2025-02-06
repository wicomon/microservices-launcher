## DEV

1. Clone repo
2. Create .env file based on template
3. Run `git submodule update --init --recursive` to rebuild the submodules
4. Run `docker compose up --build`



## PROD

1. Clone repo
2. Create .env file based on template
3. Run
```
docker compose -f docker-compose.prod.yml build
```
