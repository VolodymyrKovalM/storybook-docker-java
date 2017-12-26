# Docker with Java (Spring)

## Build tagged docker image

```
gradlew build docker
```

### Run the docker image

```
docker run -p 9000:8080 {your docker id}/{image name}
```

Access in browser on port 9000 [http://localhost:9000/](http://localhost:9000/)
