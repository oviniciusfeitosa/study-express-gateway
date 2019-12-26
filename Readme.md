# study-express-gateway

Study case of Express API Gateway.

## How to start

To start the Express API Gateway, run the following commands:

- Start API Gateway

```command
cd test3 && npm start
```

- Show current ip by host `httpbin.org/ip`

```command
curl http://httpbin.org/ip
```

- Show the same result above, but with proxy

```command
curl http://localhost:8080/ip
```

## Set API to API Gateway

```command
vim test3/config/gateway.config.yml
```
