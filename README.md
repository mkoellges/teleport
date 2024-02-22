# Teleport

## Create a config file from scratch

```bash
mkdir config
docker run -it --rm --entrypoint=teleport quay.io/gravitational/teleport:7 configure > config/teleport.yaml
```

