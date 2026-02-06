# Grafana Observability Setup Notes

## Alloy

1. Build Alloy container:

```shell
docker build -t my-alloy -f Dockerfile.alloy .
```

2. Run Alloy continer:

```shell
docker run -d --name alloy \
  --env-file .env \
  -p 12345:12345 \
  alloy
```
