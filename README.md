## Dev

1. Clone repository
2. Install dependencies
3. Create `.env` file based on `.env.template` one
4. Run NATS server
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
5. Run microservices to use
6. Run `npm run start:dev`


## PROD

Run `docker build -f dockerfile.prod -t client-gateway`