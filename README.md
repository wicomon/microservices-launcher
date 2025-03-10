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



kubectl create secret docker-registry gcr-json-key --docker-server=southamerica-east1-docker.pkg.dev --docker-username=_json_key --docker-password="$(cat '/Users/wicomon/Downloads/microservicios-450921-d696868abe5b.json')" --docker-email=wcv.dev94@gmail.com