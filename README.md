# adservice-springcloud

reimplement opentelemetry-demo-webstore's adservice with nacos registry and sentinel

## integrate list

- [x] nacos 
- [x] sentinel

## curl
```shell
grpcurl -plaintext -d '{"context_keys": ["binoculars","telescopes"]}' localhost:8080 hipstershop.AdService/GetAds
```