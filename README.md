# Node.js with Python
- npm: 5.5.1
- Node: v9.1.0
- Python: 3.6.0

----
### Pull from Docker Hub
```
docker pull davecremins/nodejs-python:latest
```

### Build from GitHub
```
docker build -t davecremins/nodejs-python github.com/davecremins/docker-nodejs-python
```

### Run image
```
docker run -it davecremins/nodejs-python bash
```

### Use as base image
```Dockerfile
FROM davecremins/nodejs-python:latest
```
