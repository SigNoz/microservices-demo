# Microservice-Demo

## Instructions to build required images

```bash
chmod +x hack/make-docker-images.sh
./hack/make-docker-images.sh
```

## To bring up Microservice-demo application

_*Note: Please update .common.env with correct SigNoz IP._

```bash
docker-compose up
```

Go to http://localhost:8080 to access Boutique UI
