# Stable Nginx Instance Template

```
git clone https://github.com/atompi/SNIT.git nginx
cd nginx
mkdir -p {data,logs,conf/ssl.d/certs}
cd conf/ssl.d/certs
openssl dhparam -out dhparams.pem 4096
# create SSL certs follow https://github.com/atompi/self-signature
docker compose up -d
```
