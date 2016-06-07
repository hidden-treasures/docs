# hidden treasures

## Solr
```
docker pull solr
docker run --name solr -d -p 8983:8983 -t solr
```

## Postgres
```
docker pull postgres
docker run --name postgres -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres:latest
```
