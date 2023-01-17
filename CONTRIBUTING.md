# Contributing


## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:lego_4.9.1_amd64.rock docker-daemon:lego:4.9.1
docker run lego:4.9.1
```
