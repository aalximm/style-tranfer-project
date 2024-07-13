# Style Transfer application

### simple description

There are 3 parts:
 - training the model
 - backend inference
 - web app aka ui

### docker-compose
Unfortunatly, there are few issues with running all application in the docker-compose.

Instead of this, you could run backend and frontend in two independent docker containers

```
  docker build -t style-transfer-back ./style-transfer-back && docker run -it style-transfer-back
  docker build -t style-transfer-front ./style-transfer-front && docker run -it style-transfer-front
```

but its better to take a look on the working app:)
https://perfect-style-transfer.netlify.app
