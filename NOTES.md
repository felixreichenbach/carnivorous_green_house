# Grafana Observability Setup Notes

## Alloy

1. Build Alloy container:

```shell
docker build -t my-alloy -f Dockerfile.alloy .
```

2. Run Alloy container:

```shell
docker run -d --name alloy \
  --env-file .env \
  -p 12345:12345 \
  alloy
```

3. Run Full Stack

```shell
docker compose up -d
```
