# Dockerfiles

> Various Docker container backend images for coco.

## Building

After cloning this repository, each image can be build with:

```bash
cd <image>
docker build -t coco/<image>:<tag>
```

> Because most images depend on `coco/base-ldap:latest`, this should be the first image you build.    
> ––––    
> If you are deploying a multi-server setup, make sure to push the images to the Docker registry after building (see `backends/docs/container_backends.md`).
