# Stable Nginx Instance Template

```
mkdir -p {data,logs,conf/ssl.d/certs}
cd conf/ssl.d/certs
openssl dhparam -out dhparams.pem 4096
docker compose up -d
```
