# opensearch-docker-compose

Navigate to the directory where you saved docker-compose.yml and start your cluster. Use the -d option to run the containers in the background.

```go
docker-compose up -d
```

Stop the cluster with the following command.

```go
docker-compose down
```

If you also with to delete the associated data volumes, use the -v option.

```go
docker-compose down -v
```
