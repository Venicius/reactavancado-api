# reactavancado-api

Comandos do docker:
<h1>Subir container</h1>
docker compose up

<h1>dump sql</h1>
docker exec -i reactavancadoapi_postgres_1 psql -h 127.0.0.1 -U strapi -d strapi -W < strapi.sql 
